# Function: <code>policy_is_shared</code>

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
In drivers/cpufreq/cpufreq_governor.c (ffffffff816b551e)
Location: include/linux/cpufreq.h:145
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_timer
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff816b688c)
Location: include/linux/cpufreq.h:145
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
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
In drivers/cpufreq/cpufreq_governor.c (ffffffff81716db1)
Location: include/linux/cpufreq.h:162
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff817183d6)
Location: include/linux/cpufreq.h:162
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
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
In kernel/sched/cpufreq_schedutil.c (ffffffff810d45af)
Location: include/linux/cpufreq.h:162
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_start
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81748b88)
Location: include/linux/cpufreq.h:162
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8174a2c8)
Location: include/linux/cpufreq.h:162
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
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
In kernel/sched/cpufreq_schedutil.c (ffffffff810d37fd)
Location: include/linux/cpufreq.h:169
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_start
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81767248)
Location: include/linux/cpufreq.h:169
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff817687d4)
Location: include/linux/cpufreq.h:169
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
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
In kernel/sched/cpufreq_schedutil.c (ffffffff810db3d5)
Location: include/linux/cpufreq.h:178
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_start
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff817dd165)
Location: include/linux/cpufreq.h:178
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff817de6c4)
Location: include/linux/cpufreq.h:178
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
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
In kernel/sched/cpufreq_schedutil.c (ffffffff810e362d)
Location: include/linux/cpufreq.h:178
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_start
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81825dd8)
Location: include/linux/cpufreq.h:178
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81827342)
Location: include/linux/cpufreq.h:178
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
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
In kernel/sched/cpufreq_schedutil.c (ffffffff810edcfd)
Location: include/linux/cpufreq.h:178
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_start
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81851cb8)
Location: include/linux/cpufreq.h:178
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81853242)
Location: include/linux/cpufreq.h:178
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
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
In kernel/sched/cpufreq_schedutil.c (ffffffff810f4c10)
Location: include/linux/cpufreq.h:182
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81895208)
Location: include/linux/cpufreq.h:182
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8189681c)
Location: include/linux/cpufreq.h:182
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
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
In kernel/sched/cpufreq_schedutil.c (ffffffff81100880)
Location: include/linux/cpufreq.h:199
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff818c7228)
Location: include/linux/cpufreq.h:199
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818c882c)
Location: include/linux/cpufreq.h:199
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
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
In kernel/sched/cpufreq_schedutil.c (ffffffff8110ade0)
Location: include/linux/cpufreq.h:199
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_start
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81999508)
Location: include/linux/cpufreq.h:199
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8199aa7c)
Location: include/linux/cpufreq.h:199
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
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
In kernel/sched/cpufreq_schedutil.c (ffffffff81107cc1)
Location: include/linux/cpufreq.h:204
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_start
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff8199c5e8)
Location: include/linux/cpufreq.h:204
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8199dbe5)
Location: include/linux/cpufreq.h:204
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
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
In kernel/sched/cpufreq_schedutil.c (ffffffff81109e06)
Location: include/linux/cpufreq.h:204
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_start
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff819812b8)
Location: include/linux/cpufreq.h:204
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff819827a7)
Location: include/linux/cpufreq.h:204
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
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
In kernel/sched/cpufreq_schedutil.c (ffffffff811283df)
Location: include/linux/cpufreq.h:208
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_start
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81a2a528)
Location: include/linux/cpufreq.h:208
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81a2bc5b)
Location: include/linux/cpufreq.h:208
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
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
In kernel/sched/build_utility.c (ffffffff8113e1f7)
Location: include/linux/cpufreq.h:215
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sugov_start
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81b9484b)
Location: include/linux/cpufreq.h:215
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81b9624a)
Location: include/linux/cpufreq.h:215
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
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
In kernel/sched/build_utility.c (ffffffff8116d7d0)
Location: include/linux/cpufreq.h:215
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sugov_start
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81d355eb)
Location: include/linux/cpufreq.h:215
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81d36e42)
Location: include/linux/cpufreq.h:215
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
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
In kernel/sched/build_utility.c (ffffffff8117e044)
Location: include/linux/cpufreq.h:214
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sugov_start
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81d9e95b)
Location: include/linux/cpufreq.h:214
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81da01da)
Location: include/linux/cpufreq.h:214
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
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
In kernel/sched/build_utility.c (ffffffff8118ae3f)
Location: include/linux/cpufreq.h:218
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sugov_start
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81e5675b)
Location: include/linux/cpufreq.h:218
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81e58059)
Location: include/linux/cpufreq.h:218
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffff800010164f10)
Location: include/linux/cpufreq.h:199
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_start
```
```
In drivers/cpufreq/cpufreq_governor.c (ffff800010b255ac)
Location: include/linux/cpufreq.h:199
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (c03b1560)
Location: include/linux/cpufreq.h:199
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_start
```
```
In drivers/cpufreq/cpufreq_governor.c (c0bff58c)
Location: include/linux/cpufreq.h:199
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (c0000000001bc058)
Location: include/linux/cpufreq.h:199
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_start
```
```
In drivers/cpufreq/cpufreq_governor.c (c000000000c1a4c0)
Location: include/linux/cpufreq.h:199
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
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
In kernel/sched/cpufreq_schedutil.c (ffffffff810f9b90)
Location: include/linux/cpufreq.h:199
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff8186b948)
Location: include/linux/cpufreq.h:199
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8186cf4c)
Location: include/linux/cpufreq.h:199
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
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
In kernel/sched/cpufreq_schedutil.c (ffffffff810e9d70)
Location: include/linux/cpufreq.h:199
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff818345f8)
Location: include/linux/cpufreq.h:199
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81835ccc)
Location: include/linux/cpufreq.h:199
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
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
In kernel/sched/cpufreq_schedutil.c (ffffffff810f6db0)
Location: include/linux/cpufreq.h:199
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff818bc6d8)
Location: include/linux/cpufreq.h:199
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818bdcdc)
Location: include/linux/cpufreq.h:199
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
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
In kernel/sched/cpufreq_schedutil.c (ffffffff81101e30)
Location: include/linux/cpufreq.h:199
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff818d89c8)
Location: include/linux/cpufreq.h:199
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818d9fec)
Location: include/linux/cpufreq.h:199
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
</details>
</li>
</ul>

## Differences
