# Function: <code>freq_qos_request_active</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff81106ea6)
Location: include/linux/pm_qos.h:279
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_add_request
```
```
In drivers/acpi/processor_thermal.c (ffffffff81637854)
Location: include/linux/pm_qos.h:279
Inline: True
```
```
In drivers/acpi/processor_perflib.c (ffffffff81637c0c)
Location: include/linux/pm_qos.h:279
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
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
In kernel/power/qos.c (ffffffff811119e6)
Location: include/linux/pm_qos.h:294
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_update_request
  - kernel/power/qos.c:freq_qos_add_request
```
```
In drivers/acpi/processor_thermal.c (ffffffff816e452c)
Location: include/linux/pm_qos.h:294
Inline: True
```
```
In drivers/acpi/processor_perflib.c (ffffffff816e4975)
Location: include/linux/pm_qos.h:294
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
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
In kernel/power/qos.c (ffffffff8110eac6)
Location: include/linux/pm_qos.h:294
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_update_request
  - kernel/power/qos.c:freq_qos_add_request
```
```
In drivers/acpi/processor_thermal.c (ffffffff81701fec)
Location: include/linux/pm_qos.h:294
Inline: True
```
```
In drivers/acpi/processor_perflib.c (ffffffff81702405)
Location: include/linux/pm_qos.h:294
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
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
In kernel/power/qos.c (ffffffff8110f566)
Location: include/linux/pm_qos.h:294
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_update_request
  - kernel/power/qos.c:freq_qos_add_request
```
```
In drivers/acpi/processor_thermal.c (ffffffff816e38cc)
Location: include/linux/pm_qos.h:294
Inline: True
```
```
In drivers/acpi/processor_perflib.c (ffffffff816e3cf5)
Location: include/linux/pm_qos.h:294
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
```
```
In drivers/powercap/dtpm_cpu.c (ffffffff819badf2)
Location: include/linux/pm_qos.h:294
Inline: True
Inline callers:
  - drivers/powercap/dtpm_cpu.c:pd_release
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
In kernel/power/qos.c (ffffffff8112eeb6)
Location: include/linux/pm_qos.h:294
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_update_request
  - kernel/power/qos.c:freq_qos_add_request
```
```
In drivers/acpi/processor_thermal.c (ffffffff8175c445)
Location: include/linux/pm_qos.h:294
Inline: True
```
```
In drivers/acpi/processor_perflib.c (ffffffff8175c972)
Location: include/linux/pm_qos.h:294
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
```
```
In drivers/powercap/dtpm_cpu.c (ffffffff81a69ef2)
Location: include/linux/pm_qos.h:294
Inline: True
Inline callers:
  - drivers/powercap/dtpm_cpu.c:pd_release
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
In kernel/power/qos.c (ffffffff81150416)
Location: include/linux/pm_qos.h:294
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_update_request
  - kernel/power/qos.c:freq_qos_add_request
```
```
In drivers/acpi/processor_thermal.c (ffffffff8188f8c3)
Location: include/linux/pm_qos.h:294
Inline: True
```
```
In drivers/acpi/processor_perflib.c (ffffffff8188ffa2)
Location: include/linux/pm_qos.h:294
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
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
In kernel/power/qos.c (ffffffff8117ed76)
Location: include/linux/pm_qos.h:294
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_update_request
  - kernel/power/qos.c:freq_qos_add_request
```
```
In drivers/acpi/processor_thermal.c (ffffffff819d2efb)
Location: include/linux/pm_qos.h:294
Inline: True
```
```
In drivers/acpi/processor_perflib.c (ffffffff819d74d2)
Location: include/linux/pm_qos.h:294
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
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
In kernel/power/qos.c (ffffffff8118f9c6)
Location: include/linux/pm_qos.h:294
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_update_request
  - kernel/power/qos.c:freq_qos_add_request
```
```
In drivers/acpi/processor_thermal.c (ffffffff81a1a51b)
Location: include/linux/pm_qos.h:294
Inline: True
```
```
In drivers/acpi/processor_perflib.c (ffffffff81a1eea5)
Location: include/linux/pm_qos.h:294
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
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
In kernel/power/qos.c (ffffffff8119e386)
Location: include/linux/pm_qos.h:294
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_update_request
  - kernel/power/qos.c:freq_qos_add_request
```
```
In drivers/acpi/processor_thermal.c (ffffffff81a65819)
Location: include/linux/pm_qos.h:294
Inline: True
```
```
In drivers/acpi/processor_perflib.c (ffffffff81a6a1c5)
Location: include/linux/pm_qos.h:294
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
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
In kernel/power/qos.c (ffff80001016dc48)
Location: include/linux/pm_qos.h:279
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_add_request
```
```
In drivers/acpi/processor_perflib.c (ffff8000107a31a0)
Location: include/linux/pm_qos.h:279
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
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
In kernel/power/qos.c (c03b8b80)
Location: include/linux/pm_qos.h:279
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_add_request
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
In kernel/power/qos.c (c0000000001c542c)
Location: include/linux/pm_qos.h:279
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_add_request
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffe00010d27a)
Location: include/linux/pm_qos.h:279
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_add_request
```
</details>
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
In kernel/power/qos.c (ffffffff811001b6)
Location: include/linux/pm_qos.h:279
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_add_request
```
```
In drivers/acpi/processor_thermal.c (ffffffff81606a84)
Location: include/linux/pm_qos.h:279
Inline: True
```
```
In drivers/acpi/processor_perflib.c (ffffffff81606e3c)
Location: include/linux/pm_qos.h:279
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
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
In kernel/power/qos.c (ffffffff810f03a6)
Location: include/linux/pm_qos.h:279
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_add_request
```
```
In drivers/acpi/processor_thermal.c (ffffffff815f1b54)
Location: include/linux/pm_qos.h:279
Inline: True
```
```
In drivers/acpi/processor_perflib.c (ffffffff815f1f0c)
Location: include/linux/pm_qos.h:279
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
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
In kernel/power/qos.c (ffffffff810fd376)
Location: include/linux/pm_qos.h:279
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_add_request
```
```
In drivers/acpi/processor_thermal.c (ffffffff8162bb34)
Location: include/linux/pm_qos.h:279
Inline: True
```
```
In drivers/acpi/processor_perflib.c (ffffffff8162beec)
Location: include/linux/pm_qos.h:279
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
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
In kernel/power/qos.c (ffffffff811085e6)
Location: include/linux/pm_qos.h:279
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_add_request
```
```
In drivers/acpi/processor_thermal.c (ffffffff816459d4)
Location: include/linux/pm_qos.h:279
Inline: True
```
```
In drivers/acpi/processor_perflib.c (ffffffff81645d8c)
Location: include/linux/pm_qos.h:279
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
```
</details>
</li>
</ul>

## Differences
