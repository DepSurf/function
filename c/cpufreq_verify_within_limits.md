# Function: <code>cpufreq_verify_within_limits</code>

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
In drivers/acpi/processor_thermal.c (ffffffff814ae738)
Location: include/linux/cpufreq.h:326
Inline: True
```
```
In drivers/acpi/processor_perflib.c (ffffffff814af30f)
Location: include/linux/cpufreq.h:326
Inline: True
```
```
In drivers/cpufreq/freq_table.c (ffffffff816b2954)
Location: include/linux/cpufreq.h:326
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff816b8df8)
Location: include/linux/cpufreq.h:326
Inline: True
Inline callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_verify
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff816b9c18)
Location: include/linux/cpufreq.h:326
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
In drivers/acpi/processor_thermal.c (ffffffff814fe102)
Location: include/linux/cpufreq.h:368
Inline: True
```
```
In drivers/acpi/processor_perflib.c (ffffffff814fec53)
Location: include/linux/cpufreq.h:368
Inline: True
```
```
In drivers/cpufreq/freq_table.c (ffffffff817146ec)
Location: include/linux/cpufreq.h:368
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff8171a848)
Location: include/linux/cpufreq.h:368
Inline: True
Inline callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_verify
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8171b6f8)
Location: include/linux/cpufreq.h:368
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
In drivers/acpi/processor_thermal.c (ffffffff81520dfd)
Location: include/linux/cpufreq.h:372
Inline: True
```
```
In drivers/acpi/processor_perflib.c (ffffffff8152185b)
Location: include/linux/cpufreq.h:372
Inline: True
```
```
In drivers/cpufreq/freq_table.c (ffffffff8174649c)
Location: include/linux/cpufreq.h:372
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff8174c638)
Location: include/linux/cpufreq.h:372
Inline: True
Inline callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_verify
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8174ee56)
Location: include/linux/cpufreq.h:372
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
In drivers/acpi/processor_thermal.c (ffffffff815325a3)
Location: include/linux/cpufreq.h:379
Inline: True
```
```
In drivers/acpi/processor_perflib.c (ffffffff81532bc3)
Location: include/linux/cpufreq.h:379
Inline: True
```
```
In drivers/cpufreq/freq_table.c (ffffffff81764aac)
Location: include/linux/cpufreq.h:379
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff8176acc8)
Location: include/linux/cpufreq.h:379
Inline: True
Inline callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_verify
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8176dbd2)
Location: include/linux/cpufreq.h:379
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_policy
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
In drivers/acpi/processor_thermal.c (ffffffff81593b53)
Location: include/linux/cpufreq.h:394
Inline: True
```
```
In drivers/acpi/processor_perflib.c (ffffffff81594173)
Location: include/linux/cpufreq.h:394
Inline: True
```
```
In drivers/cpufreq/freq_table.c (ffffffff817daa8c)
Location: include/linux/cpufreq.h:394
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff817e0ba8)
Location: include/linux/cpufreq.h:394
Inline: True
Inline callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_verify
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff817e35d2)
Location: include/linux/cpufreq.h:394
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_policy
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
In drivers/acpi/processor_thermal.c (ffffffff815cb15d)
Location: include/linux/cpufreq.h:394
Inline: True
```
```
In drivers/acpi/processor_perflib.c (ffffffff815cb70d)
Location: include/linux/cpufreq.h:394
Inline: True
```
```
In drivers/cpufreq/freq_table.c (ffffffff8182371c)
Location: include/linux/cpufreq.h:394
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff818298a8)
Location: include/linux/cpufreq.h:394
Inline: True
Inline callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_verify
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8182c212)
Location: include/linux/cpufreq.h:394
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_policy
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
In drivers/acpi/processor_thermal.c (ffffffff815e473d)
Location: include/linux/cpufreq.h:386
Inline: True
```
```
In drivers/acpi/processor_perflib.c (ffffffff815e4ced)
Location: include/linux/cpufreq.h:386
Inline: True
```
```
In drivers/cpufreq/freq_table.c (ffffffff8184f5dc)
Location: include/linux/cpufreq.h:386
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff81855768)
Location: include/linux/cpufreq.h:386
Inline: True
Inline callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_verify
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818581c2)
Location: include/linux/cpufreq.h:386
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_policy
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
In drivers/acpi/processor_thermal.c (ffffffff8161631c)
Location: include/linux/cpufreq.h:415
Inline: True
```
```
In drivers/acpi/processor_perflib.c (ffffffff816168df)
Location: include/linux/cpufreq.h:415
Inline: True
```
```
In drivers/cpufreq/freq_table.c (ffffffff81892acc)
Location: include/linux/cpufreq.h:415
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff81898df8)
Location: include/linux/cpufreq.h:415
Inline: True
Inline callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_verify
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8189ba50)
Location: include/linux/cpufreq.h:415
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_policy
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
In drivers/cpufreq/freq_table.c (ffffffff818c4afc)
Location: include/linux/cpufreq.h:430
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff818cade8)
Location: include/linux/cpufreq.h:430
Inline: True
Inline callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_verify
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818cdca2)
Location: include/linux/cpufreq.h:430
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_policy
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
In drivers/cpufreq/freq_table.c (ffffffff81996ddc)
Location: include/linux/cpufreq.h:432
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff8199d108)
Location: include/linux/cpufreq.h:432
Inline: True
Inline callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_verify
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff819a01ad)
Location: include/linux/cpufreq.h:432
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_cpu_policy
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
In drivers/cpufreq/freq_table.c (ffffffff81999f15)
Location: include/linux/cpufreq.h:456
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff8199fd3e)
Location: include/linux/cpufreq.h:456
Inline: True
Inline callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_verify
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff819a3428)
Location: include/linux/cpufreq.h:456
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_cpu_policy
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
In drivers/cpufreq/freq_table.c (ffffffff8197eaf5)
Location: include/linux/cpufreq.h:450
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff8198496e)
Location: include/linux/cpufreq.h:450
Inline: True
Inline callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_verify
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81988018)
Location: include/linux/cpufreq.h:450
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_cpu_policy
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
In drivers/cpufreq/freq_table.c (ffffffff81a27c65)
Location: include/linux/cpufreq.h:447
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff81a2e06e)
Location: include/linux/cpufreq.h:447
Inline: True
Inline callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_verify
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81a318a3)
Location: include/linux/cpufreq.h:447
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_cpu_policy
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
In drivers/cpufreq/freq_table.c (ffffffff81b91a95)
Location: include/linux/cpufreq.h:463
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
```
```
In drivers/cpufreq/amd-pstate.c (ffffffff81b96a3e)
Location: include/linux/cpufreq.h:463
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate.c:amd_pstate_verify
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff81b99a2e)
Location: include/linux/cpufreq.h:463
Inline: True
Inline callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_verify
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81b9db26)
Location: include/linux/cpufreq.h:463
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_cpu_policy
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
In drivers/cpufreq/freq_table.c (ffffffff81d31e65)
Location: include/linux/cpufreq.h:463
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
```
```
In drivers/cpufreq/amd-pstate.c (ffffffff81d376be)
Location: include/linux/cpufreq.h:463
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate.c:amd_pstate_verify
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff81d3ae0e)
Location: include/linux/cpufreq.h:463
Inline: True
Inline callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_verify
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81d3f626)
Location: include/linux/cpufreq.h:463
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_cpu_policy
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
In drivers/cpufreq/freq_table.c (ffffffff81d9b245)
Location: include/linux/cpufreq.h:466
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
```
```
In drivers/cpufreq/amd-pstate.c (ffffffff81da217e)
Location: include/linux/cpufreq.h:466
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate.c:amd_pstate_verify
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff81da590e)
Location: include/linux/cpufreq.h:466
Inline: True
Inline callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_verify
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81daa196)
Location: include/linux/cpufreq.h:466
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_cpu_policy
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
In drivers/cpufreq/freq_table.c (ffffffff81e52fc5)
Location: include/linux/cpufreq.h:470
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
```
```
In drivers/cpufreq/amd-pstate.c (ffffffff81e5a0be)
Location: include/linux/cpufreq.h:470
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate.c:amd_pstate_verify
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff81e5d9ce)
Location: include/linux/cpufreq.h:470
Inline: True
Inline callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_verify
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81e62339)
Location: include/linux/cpufreq.h:470
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_cpu_policy
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
In drivers/cpufreq/freq_table.c (ffff800010b226d4)
Location: include/linux/cpufreq.h:430
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
In drivers/cpufreq/freq_table.c (c0bfcaf8)
Location: include/linux/cpufreq.h:430
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
In drivers/cpufreq/freq_table.c (c000000000c167ec)
Location: include/linux/cpufreq.h:430
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/freq_table.c (ffffffff8186921c)
Location: include/linux/cpufreq.h:430
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818718a2)
Location: include/linux/cpufreq.h:430
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_policy
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
In drivers/cpufreq/freq_table.c (ffffffff81831ecc)
Location: include/linux/cpufreq.h:430
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff81838298)
Location: include/linux/cpufreq.h:430
Inline: True
Inline callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_verify
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8183b05c)
Location: include/linux/cpufreq.h:430
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_policy
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
In drivers/cpufreq/freq_table.c (ffffffff818b9fac)
Location: include/linux/cpufreq.h:430
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff818c0298)
Location: include/linux/cpufreq.h:430
Inline: True
Inline callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_verify
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818c3152)
Location: include/linux/cpufreq.h:430
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_policy
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
In drivers/cpufreq/freq_table.c (ffffffff818d628c)
Location: include/linux/cpufreq.h:430
Inline: True
Inline callers:
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
  - drivers/cpufreq/freq_table.c:cpufreq_frequency_table_verify
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff818dc5a8)
Location: include/linux/cpufreq.h:430
Inline: True
Inline callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_verify
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818df4b2)
Location: include/linux/cpufreq.h:430
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy
  - drivers/cpufreq/intel_pstate.c:intel_pstate_verify_policy
```
</details>
</li>
</ul>

## Differences
