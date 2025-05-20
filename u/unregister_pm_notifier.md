# Function: <code>unregister_pm_notifier</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int unregister_pm_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810ccc50)
Location: kernel/power/main.c:35
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_graph
  - drivers/acpi/battery.c:acpi_battery_remove
  - drivers/base/firmware_class.c:firmware_class_exit
  - drivers/thermal/thermal_core.c:thermal_exit
  - drivers/mmc/core/host.c:mmc_remove_host
```
**Symbols:**

```
ffffffff810ccc50-ffffffff810ccc6a: unregister_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int unregister_pm_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810d16f0)
Location: kernel/power/main.c:35
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_graph
  - drivers/acpi/battery.c:acpi_battery_remove
  - drivers/base/firmware_class.c:firmware_class_exit
  - drivers/thermal/thermal_core.c:thermal_exit
  - drivers/mmc/core/core.c:mmc_unregister_pm_notifier
```
**Symbols:**

```
ffffffff810d16f0-ffffffff810d170a: unregister_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int unregister_pm_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810d8150)
Location: kernel/power/main.c:35
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_graph
  - drivers/acpi/battery.c:acpi_battery_remove
  - drivers/base/firmware_class.c:firmware_class_exit
  - drivers/thermal/thermal_core.c:thermal_exit
  - drivers/mmc/core/core.c:mmc_unregister_pm_notifier
```
**Symbols:**

```
ffffffff810d8150-ffffffff810d816a: unregister_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int unregister_pm_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810d7190)
Location: kernel/power/main.c:35
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_graph
  - drivers/acpi/battery.c:acpi_battery_remove
  - drivers/base/firmware_class.c:firmware_class_exit
  - drivers/thermal/thermal_core.c:thermal_exit
  - drivers/mmc/core/core.c:mmc_unregister_pm_notifier
```
**Symbols:**

```
ffffffff810d7190-ffffffff810d71aa: unregister_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int unregister_pm_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810df130)
Location: kernel/power/main.c:35
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_graph
  - drivers/acpi/battery.c:acpi_battery_remove
  - drivers/base/firmware_class.c:firmware_class_exit
  - drivers/thermal/thermal_core.c:thermal_exit
  - drivers/mmc/core/core.c:mmc_unregister_pm_notifier
```
**Symbols:**

```
ffffffff810df130-ffffffff810df14a: unregister_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int unregister_pm_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810e77d0)
Location: kernel/power/main.c:64
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_graph
  - drivers/acpi/battery.c:acpi_battery_remove
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/thermal/thermal_core.c:thermal_exit
  - drivers/mmc/core/core.c:mmc_unregister_pm_notifier
```
**Symbols:**

```
ffffffff810e77d0-ffffffff810e77ea: unregister_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int unregister_pm_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810f2dd0)
Location: kernel/power/main.c:64
Inline: False
Direct callers:
  - kernel/trace/fgraph.c:unregister_ftrace_graph
  - drivers/acpi/battery.c:acpi_battery_remove
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/thermal/thermal_core.c:thermal_exit
  - drivers/mmc/core/core.c:mmc_unregister_pm_notifier
```
**Symbols:**

```
ffffffff810f2dd0-ffffffff810f2dea: unregister_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int unregister_pm_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810fb2a0)
Location: kernel/power/main.c:76
Inline: False
Direct callers:
  - kernel/trace/fgraph.c:unregister_ftrace_graph
  - drivers/acpi/battery.c:acpi_battery_remove
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/mfd/twl6030-irq.c:twl6030_exit_irq
  - drivers/mmc/core/core.c:mmc_unregister_pm_notifier
```
**Symbols:**

```
ffffffff810fb2a0-ffffffff810fb2ba: unregister_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int unregister_pm_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81107450)
Location: kernel/power/main.c:77
Inline: False
Direct callers:
  - kernel/trace/fgraph.c:unregister_ftrace_graph
  - drivers/acpi/battery.c:acpi_battery_remove
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/mfd/twl6030-irq.c:twl6030_exit_irq
  - drivers/mmc/core/core.c:mmc_unregister_pm_notifier
```
**Symbols:**

```
ffffffff81107450-ffffffff8110746a: unregister_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int unregister_pm_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81111f50)
Location: kernel/power/main.c:77
Inline: False
Direct callers:
  - kernel/trace/fgraph.c:unregister_ftrace_graph
  - drivers/acpi/battery.c:acpi_battery_remove
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/mmc/core/core.c:mmc_unregister_pm_notifier
```
**Symbols:**

```
ffffffff81111f50-ffffffff81111f6a: unregister_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int unregister_pm_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff8110f020)
Location: kernel/power/main.c:77
Inline: False
Direct callers:
  - kernel/trace/fgraph.c:unregister_ftrace_graph
  - drivers/acpi/battery.c:acpi_battery_remove
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/mmc/core/core.c:mmc_unregister_pm_notifier
```
**Symbols:**

```
ffffffff8110f020-ffffffff8110f03a: unregister_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int unregister_pm_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff8110fac0)
Location: kernel/power/main.c:77
Inline: False
Direct callers:
  - kernel/trace/fgraph.c:unregister_ftrace_graph
  - drivers/acpi/battery.c:acpi_battery_remove
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/base/firmware_loader/main.c:firmware_class_init
```
**Symbols:**

```
ffffffff8110fac0-ffffffff8110fada: unregister_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int unregister_pm_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff8112f410)
Location: kernel/power/main.c:77
Inline: False
Direct callers:
  - kernel/trace/fgraph.c:unregister_ftrace_graph
  - drivers/acpi/battery.c:acpi_battery_remove
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/base/firmware_loader/main.c:firmware_class_init
```
**Symbols:**

```
ffffffff8112f410-ffffffff8112f42a: unregister_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int unregister_pm_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81150a80)
Location: kernel/power/main.c:77
Inline: False
Direct callers:
  - kernel/trace/fgraph.c:unregister_ftrace_graph
  - drivers/acpi/battery.c:acpi_battery_remove
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/base/firmware_loader/main.c:firmware_class_init
```
**Symbols:**

```
ffffffff81150a80-ffffffff81150aa2: unregister_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int unregister_pm_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff8117f4d0)
Location: kernel/power/main.c:80
Inline: False
Direct callers:
  - kernel/trace/fgraph.c:unregister_ftrace_graph
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/base/firmware_loader/main.c:firmware_class_init
```
**Symbols:**

```
ffffffff8117f4d0-ffffffff8117f4f2: unregister_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int unregister_pm_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff811901e0)
Location: kernel/power/main.c:108
Inline: False
Direct callers:
  - kernel/trace/fgraph.c:unregister_ftrace_graph
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/base/firmware_loader/main.c:firmware_class_init
```
**Symbols:**

```
ffffffff811901e0-ffffffff81190202: unregister_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int unregister_pm_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff8119eba0)
Location: kernel/power/main.c:92
Inline: False
Direct callers:
  - kernel/trace/fgraph.c:unregister_ftrace_graph
  - drivers/acpi/battery.c:acpi_battery_remove
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/base/firmware_loader/main.c:firmware_class_init
```
**Symbols:**

```
ffffffff8119eba0-ffffffff8119ebc2: unregister_pm_notifier (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int unregister_pm_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffff80001016e3d0)
Location: kernel/power/main.c:77
Inline: False
Direct callers:
  - kernel/trace/fgraph.c:unregister_ftrace_graph
  - drivers/acpi/battery.c:acpi_battery_remove
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/mfd/twl6030-irq.c:twl6030_exit_irq
  - drivers/mmc/core/core.c:mmc_unregister_pm_notifier
```
**Symbols:**

```
ffff80001016e3d0-ffff80001016e404: unregister_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int unregister_pm_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (c03b91b0)
Location: kernel/power/main.c:77
Inline: False
Direct callers:
  - kernel/trace/fgraph.c:unregister_ftrace_graph
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/mfd/twl6030-irq.c:twl6030_exit_irq
  - drivers/mmc/core/core.c:mmc_unregister_pm_notifier
```
**Symbols:**

```
c03b91b0-c03b91d8: unregister_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int unregister_pm_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (c0000000001c5d30)
Location: kernel/power/main.c:77
Inline: False
Direct callers:
  - kernel/trace/fgraph.c:unregister_ftrace_graph
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/mfd/twl6030-irq.c:twl6030_exit_irq
  - drivers/mmc/core/core.c:mmc_unregister_pm_notifier
```
**Symbols:**

```
c0000000001c5d30-c0000000001c5d70: unregister_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (0)
Location: include/linux/suspend.h:517
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/suspend.h:517
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int unregister_pm_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81100760)
Location: kernel/power/main.c:77
Inline: False
Direct callers:
  - kernel/trace/fgraph.c:unregister_ftrace_graph
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/mmc/core/core.c:mmc_unregister_pm_notifier
```
**Symbols:**

```
ffffffff81100760-ffffffff8110077a: unregister_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int unregister_pm_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810f0950)
Location: kernel/power/main.c:77
Inline: False
Direct callers:
  - kernel/trace/fgraph.c:unregister_ftrace_graph
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/base/firmware_loader/main.c:firmware_class_init
```
**Symbols:**

```
ffffffff810f0950-ffffffff810f096a: unregister_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int unregister_pm_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810fd920)
Location: kernel/power/main.c:77
Inline: False
Direct callers:
  - kernel/trace/fgraph.c:unregister_ftrace_graph
  - drivers/acpi/battery.c:acpi_battery_remove
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/mfd/twl6030-irq.c:twl6030_exit_irq
  - drivers/mmc/core/core.c:mmc_unregister_pm_notifier
```
**Symbols:**

```
ffffffff810fd920-ffffffff810fd93a: unregister_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int unregister_pm_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81108be0)
Location: kernel/power/main.c:77
Inline: False
Direct callers:
  - kernel/trace/fgraph.c:unregister_ftrace_graph
  - drivers/acpi/battery.c:acpi_battery_remove
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/mfd/twl6030-irq.c:twl6030_exit_irq
  - drivers/mmc/core/core.c:mmc_unregister_pm_notifier
```
**Symbols:**

```
ffffffff81108be0-ffffffff81108bfa: unregister_pm_notifier (STB_GLOBAL)
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
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
