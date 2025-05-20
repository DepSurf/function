# Function: <code>kstrtou64</code>

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
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff810442af)
Location: include/linux/kernel.h:335
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:set_bank
  - arch/x86/kernel/cpu/mcheck/mce.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mcheck/mce.c:set_ignore_ce
```
```
In kernel/power/wakelock.c (ffffffff810d63f4)
Location: include/linux/kernel.h:335
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_lock
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
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81044429)
Location: include/linux/kernel.h:342
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mcheck/mce.c:set_ignore_ce
  - arch/x86/kernel/cpu/mcheck/mce.c:set_bank
```
```
In kernel/power/wakelock.c (ffffffff810db273)
Location: include/linux/kernel.h:342
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_lock
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
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81045f19)
Location: include/linux/kernel.h:344
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mcheck/mce.c:set_ignore_ce
  - arch/x86/kernel/cpu/mcheck/mce.c:set_bank
```
```
In kernel/power/wakelock.c (ffffffff810e1d43)
Location: include/linux/kernel.h:344
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_lock
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
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81045c09)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mcheck/mce.c:set_ignore_ce
  - arch/x86/kernel/cpu/mcheck/mce.c:set_bank
```
```
In kernel/power/wakelock.c (ffffffff810e0e8d)
Location: include/linux/kernel.h:357
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_lock
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
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81049429)
Location: include/linux/kernel.h:394
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mcheck/mce.c:set_ignore_ce
  - arch/x86/kernel/cpu/mcheck/mce.c:set_bank
```
```
In kernel/power/wakelock.c (ffffffff810e915d)
Location: include/linux/kernel.h:394
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_lock
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
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104bc99)
Location: include/linux/kernel.h:410
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mcheck/mce.c:set_ignore_ce
  - arch/x86/kernel/cpu/mcheck/mce.c:set_bank
```
```
In kernel/power/wakelock.c (ffffffff810f1476)
Location: include/linux/kernel.h:410
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_lock
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff81049379)
Location: include/linux/kernel.h:443
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
```
```
In kernel/power/wakelock.c (ffffffff810fcb06)
Location: include/linux/kernel.h:443
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_lock
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
In arch/x86/kernel/cpu/intel_epb.c (ffffffff81049a76)
Location: include/linux/kernel.h:402
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104c1c9)
Location: include/linux/kernel.h:402
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
```
```
In kernel/power/wakelock.c (ffffffff8110513b)
Location: include/linux/kernel.h:402
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_lock
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
In arch/x86/kernel/cpu/intel_epb.c (ffffffff8104a406)
Location: include/linux/kernel.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104cb89)
Location: include/linux/kernel.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
```
```
In kernel/power/wakelock.c (ffffffff811114db)
Location: include/linux/kernel.h:406
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_lock
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
In arch/x86/kernel/cpu/intel_epb.c (ffffffff8104e9a6)
Location: include/linux/kernel.h:395
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81051759)
Location: include/linux/kernel.h:395
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
```
```
In kernel/power/wakelock.c (ffffffff8111c5ab)
Location: include/linux/kernel.h:395
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_lock
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
In arch/x86/kernel/cpu/intel_epb.c (ffffffff8104dcb6)
Location: include/linux/kernel.h:247
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81050a19)
Location: include/linux/kernel.h:247
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
```
```
In kernel/power/wakelock.c (ffffffff81116f0b)
Location: include/linux/kernel.h:247
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_lock
```
```
In drivers/pwm/sysfs.c (ffffffff816432a9)
Location: include/linux/kernel.h:247
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:duty_cycle_store
  - drivers/pwm/sysfs.c:period_store
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
In arch/x86/kernel/cpu/intel_epb.c (ffffffff8104f946)
Location: include/linux/kernel.h:257
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810523c9)
Location: include/linux/kernel.h:257
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
```
```
In kernel/power/wakelock.c (ffffffff8111763b)
Location: include/linux/kernel.h:257
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_lock
```
```
In drivers/pwm/sysfs.c (ffffffff816260c9)
Location: include/linux/kernel.h:257
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:duty_cycle_store
  - drivers/pwm/sysfs.c:period_store
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
In arch/x86/kernel/cpu/intel_epb.c (ffffffff81057b80)
Location: include/linux/kstrtox.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105a8db)
Location: include/linux/kstrtox.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
```
```
In kernel/power/wakelock.c (ffffffff8113799b)
Location: include/linux/kstrtox.h:74
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_lock
```
```
In drivers/pwm/sysfs.c (ffffffff816958b9)
Location: include/linux/kstrtox.h:74
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:duty_cycle_store
  - drivers/pwm/sysfs.c:period_store
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
In arch/x86/kernel/cpu/intel_epb.c (ffffffff8106402c)
Location: include/linux/kstrtox.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810675a3)
Location: include/linux/kstrtox.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
```
```
In kernel/power/wakelock.c (ffffffff81159fe8)
Location: include/linux/kstrtox.h:74
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_lock
```
```
In drivers/pwm/sysfs.c (ffffffff817b6627)
Location: include/linux/kstrtox.h:74
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:duty_cycle_store
  - drivers/pwm/sysfs.c:period_store
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
In arch/x86/kernel/cpu/intel_epb.c (ffffffff810731ac)
Location: include/linux/kstrtox.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81076b83)
Location: include/linux/kstrtox.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
```
```
In kernel/power/wakelock.c (ffffffff8118c2b8)
Location: include/linux/kstrtox.h:74
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_lock
```
```
In drivers/pwm/sysfs.c (ffffffff818d0bd7)
Location: include/linux/kstrtox.h:74
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:duty_cycle_store
  - drivers/pwm/sysfs.c:period_store
```
```
In drivers/acpi/utils.c (ffffffff8195671a)
Location: include/linux/kstrtox.h:74
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_dev_uid_to_integer
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
In arch/x86/kernel/cpu/intel_epb.c (ffffffff81074d8c)
Location: include/linux/kstrtox.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81078e03)
Location: include/linux/kstrtox.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
```
```
In kernel/power/wakelock.c (ffffffff8119d9d8)
Location: include/linux/kstrtox.h:74
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_lock
```
```
In drivers/pwm/sysfs.c (ffffffff81913b67)
Location: include/linux/kstrtox.h:74
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:duty_cycle_store
  - drivers/pwm/sysfs.c:period_store
```
```
In drivers/acpi/utils.c (ffffffff8199cb1a)
Location: include/linux/kstrtox.h:74
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_dev_uid_to_integer
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
In arch/x86/kernel/cpu/intel_epb.c (ffffffff8107c25c)
Location: include/linux/kstrtox.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810803b3)
Location: include/linux/kstrtox.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
```
```
In kernel/power/wakelock.c (ffffffff811acb48)
Location: include/linux/kstrtox.h:74
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_lock
```
```
In kernel/cgroup/misc.c (ffffffff8124f2e8)
Location: include/linux/kstrtox.h:74
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_max_write
```
```
In drivers/pwm/sysfs.c (ffffffff8195baa7)
Location: include/linux/kstrtox.h:74
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:duty_cycle_store
  - drivers/pwm/sysfs.c:period_store
```
```
In drivers/acpi/utils.c (ffffffff819e4b8a)
Location: include/linux/kstrtox.h:74
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_dev_uid_to_integer
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
In kernel/power/wakelock.c (ffff800010171960)
Location: include/linux/kernel.h:406
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_lock
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
In kernel/power/wakelock.c (c03c42cc)
Location: include/linux/kernel.h:406
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_lock
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
In arch/powerpc/platforms/pseries/mobility.c (c0000000000f49cc)
Location: include/linux/kernel.h:406
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/mobility.c:migration_store
```
```
In kernel/power/wakelock.c (c0000000001ca0d0)
Location: include/linux/kernel.h:406
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_lock
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
In arch/x86/kernel/cpu/intel_epb.c (ffffffff8104a576)
Location: include/linux/kernel.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104ccf9)
Location: include/linux/kernel.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
```
```
In kernel/power/wakelock.c (ffffffff81109abb)
Location: include/linux/kernel.h:406
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_lock
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
In arch/x86/kernel/cpu/intel_epb.c (ffffffff81039986)
Location: include/linux/kernel.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103c179)
Location: include/linux/kernel.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
```
```
In kernel/power/wakelock.c (ffffffff810fa99b)
Location: include/linux/kernel.h:406
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_lock
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
In arch/x86/kernel/cpu/intel_epb.c (ffffffff8104a3b6)
Location: include/linux/kernel.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104cb39)
Location: include/linux/kernel.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
```
```
In kernel/power/wakelock.c (ffffffff811079ab)
Location: include/linux/kernel.h:406
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_lock
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
In arch/x86/kernel/cpu/intel_epb.c (ffffffff8104b7c6)
Location: include/linux/kernel.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104df49)
Location: include/linux/kernel.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
```
```
In kernel/power/wakelock.c (ffffffff81112d5b)
Location: include/linux/kernel.h:406
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_lock
```
</details>
</li>
</ul>

## Differences
