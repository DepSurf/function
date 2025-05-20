# Function: <code>cpufreq_verify_within_cpu_limits</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/freq_table.c (ffffffff816b294f)
Location: include/linux/cpufreq.h:343
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff816b8df5)
Location: include/linux/cpufreq.h:343
Inline: True
Inline callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_verify
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff816b9c15)
Location: include/linux/cpufreq.h:343
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/freq_table.c (ffffffff817146e7)
Location: include/linux/cpufreq.h:385
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff8171a845)
Location: include/linux/cpufreq.h:385
Inline: True
Inline callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_verify
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8171b6f5)
Location: include/linux/cpufreq.h:385
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/freq_table.c (ffffffff81746497)
Location: include/linux/cpufreq.h:389
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff8174c635)
Location: include/linux/cpufreq.h:389
Inline: True
Inline callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_verify
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8174ee53)
Location: include/linux/cpufreq.h:389
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/freq_table.c (ffffffff81764aa7)
Location: include/linux/cpufreq.h:396
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff8176acc5)
Location: include/linux/cpufreq.h:396
Inline: True
Inline callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_verify
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/freq_table.c (ffffffff817daa87)
Location: include/linux/cpufreq.h:411
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff817e0ba5)
Location: include/linux/cpufreq.h:411
Inline: True
Inline callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_verify
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/freq_table.c (ffffffff81823717)
Location: include/linux/cpufreq.h:411
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff818298a5)
Location: include/linux/cpufreq.h:411
Inline: True
Inline callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_verify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/freq_table.c (ffffffff8184f5d7)
Location: include/linux/cpufreq.h:403
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff81855765)
Location: include/linux/cpufreq.h:403
Inline: True
Inline callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_verify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/freq_table.c (ffffffff81892ac7)
Location: include/linux/cpufreq.h:432
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff81898df5)
Location: include/linux/cpufreq.h:432
Inline: True
Inline callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_verify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/freq_table.c (ffffffff818c4af7)
Location: include/linux/cpufreq.h:448
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff818cade5)
Location: include/linux/cpufreq.h:448
Inline: True
Inline callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_verify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/freq_table.c (ffffffff81996dd7)
Location: include/linux/cpufreq.h:450
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff8199d105)
Location: include/linux/cpufreq.h:450
Inline: True
Inline callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_verify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/freq_table.c (ffffffff81999f07)
Location: include/linux/cpufreq.h:474
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff8199fd35)
Location: include/linux/cpufreq.h:474
Inline: True
Inline callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_verify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/freq_table.c (ffffffff8197eae7)
Location: include/linux/cpufreq.h:468
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff81984965)
Location: include/linux/cpufreq.h:468
Inline: True
Inline callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_verify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/freq_table.c (ffffffff81a27c57)
Location: include/linux/cpufreq.h:465
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff81a2e065)
Location: include/linux/cpufreq.h:465
Inline: True
Inline callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_verify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/freq_table.c (ffffffff81b91a87)
Location: include/linux/cpufreq.h:481
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
```
```
In drivers/cpufreq/amd-pstate.c (ffffffff81b96a35)
Location: include/linux/cpufreq.h:481
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate.c:amd_pstate_verify
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff81b99a25)
Location: include/linux/cpufreq.h:481
Inline: True
Inline callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_verify
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/freq_table.c (ffffffff81d31e57)
Location: include/linux/cpufreq.h:481
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
```
```
In drivers/cpufreq/amd-pstate.c (ffffffff81d376b5)
Location: include/linux/cpufreq.h:481
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate.c:amd_pstate_verify
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff81d3ae05)
Location: include/linux/cpufreq.h:481
Inline: True
Inline callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_verify
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/freq_table.c (ffffffff81d9b237)
Location: include/linux/cpufreq.h:484
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
```
```
In drivers/cpufreq/amd-pstate.c (ffffffff81da2175)
Location: include/linux/cpufreq.h:484
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate.c:amd_pstate_verify
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff81da5905)
Location: include/linux/cpufreq.h:484
Inline: True
Inline callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_verify
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/freq_table.c (ffffffff81e52fb7)
Location: include/linux/cpufreq.h:479
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
```
```
In drivers/cpufreq/amd-pstate.c (ffffffff81e5a0b5)
Location: include/linux/cpufreq.h:479
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate.c:amd_pstate_verify
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff81e5d9c5)
Location: include/linux/cpufreq.h:479
Inline: True
Inline callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_verify
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
In drivers/cpufreq/freq_table.c (ffff800010b226d0)
Location: include/linux/cpufreq.h:448
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
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
In drivers/cpufreq/freq_table.c (c0bfcaf4)
Location: include/linux/cpufreq.h:448
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
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
In drivers/cpufreq/freq_table.c (c000000000c167e0)
Location: include/linux/cpufreq.h:448
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
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
In drivers/cpufreq/freq_table.c (ffffffff81869217)
Location: include/linux/cpufreq.h:448
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/freq_table.c (ffffffff81831ec7)
Location: include/linux/cpufreq.h:448
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff81838295)
Location: include/linux/cpufreq.h:448
Inline: True
Inline callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_verify
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/freq_table.c (ffffffff818b9fa7)
Location: include/linux/cpufreq.h:448
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff818c0295)
Location: include/linux/cpufreq.h:448
Inline: True
Inline callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_verify
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/freq_table.c (ffffffff818d6287)
Location: include/linux/cpufreq.h:448
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff818dc5a5)
Location: include/linux/cpufreq.h:448
Inline: True
Inline callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_verify
```
</details>
</li>
</ul>

## Differences
