# Function: <code>register_pm_notifier</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int register_pm_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810ccc30)
Location: kernel/power/main.c:29
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_pm_sync_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/trace/ftrace.c:register_ftrace_graph
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/base/firmware_class.c:firmware_class_init
  - arch/x86/power/cpu.c:bsp_pm_check_init
```
**Symbols:**

```
ffffffff810ccc30-ffffffff810ccc4a: register_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int register_pm_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810d16d0)
Location: kernel/power/main.c:29
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_pm_sync_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/trace/ftrace.c:register_ftrace_graph
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/base/firmware_class.c:firmware_class_init
  - drivers/mmc/core/core.c:mmc_register_pm_notifier
  - arch/x86/power/cpu.c:bsp_pm_check_init
```
**Symbols:**

```
ffffffff810d16d0-ffffffff810d16ea: register_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int register_pm_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810d8130)
Location: kernel/power/main.c:29
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_pm_sync_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/trace/ftrace.c:register_ftrace_graph
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/base/power/trace.c:early_resume_init
  - drivers/base/firmware_class.c:firmware_class_init
  - drivers/mmc/core/core.c:mmc_register_pm_notifier
  - arch/x86/power/cpu.c:bsp_pm_check_init
```
**Symbols:**

```
ffffffff810d8130-ffffffff810d814a: register_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int register_pm_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810d7170)
Location: kernel/power/main.c:29
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_pm_sync_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/trace/ftrace.c:register_ftrace_graph
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/base/power/trace.c:early_resume_init
  - drivers/base/firmware_class.c:firmware_class_init
  - drivers/mmc/core/core.c:mmc_register_pm_notifier
  - arch/x86/power/cpu.c:bsp_pm_check_init
```
**Symbols:**

```
ffffffff810d7170-ffffffff810d718a: register_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int register_pm_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810df110)
Location: kernel/power/main.c:29
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_pm_sync_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/trace/ftrace.c:register_ftrace_graph
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/base/power/trace.c:early_resume_init
  - drivers/base/firmware_class.c:firmware_class_init
  - drivers/mmc/core/core.c:mmc_register_pm_notifier
  - arch/x86/power/cpu.c:bsp_pm_check_init
```
**Symbols:**

```
ffffffff810df110-ffffffff810df12a: register_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int register_pm_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810e77b0)
Location: kernel/power/main.c:58
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_pm_sync_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/trace/ftrace.c:register_ftrace_graph
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/base/power/trace.c:early_resume_init
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/mmc/core/core.c:mmc_register_pm_notifier
  - arch/x86/power/cpu.c:bsp_pm_check_init
```
**Symbols:**

```
ffffffff810e77b0-ffffffff810e77ca: register_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int register_pm_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810f2db0)
Location: kernel/power/main.c:58
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_pm_sync_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/hung_task.c:hung_task_init
  - kernel/trace/fgraph.c:register_ftrace_graph
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/base/power/trace.c:early_resume_init
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/mmc/core/core.c:mmc_register_pm_notifier
  - arch/x86/power/cpu.c:bsp_pm_check_init
```
**Symbols:**

```
ffffffff810f2db0-ffffffff810f2dca: register_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int register_pm_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810fb280)
Location: kernel/power/main.c:70
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_pm_sync_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/hung_task.c:hung_task_init
  - kernel/trace/fgraph.c:register_ftrace_graph
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/base/power/trace.c:early_resume_init
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/mmc/core/core.c:mmc_register_pm_notifier
  - arch/x86/power/cpu.c:bsp_pm_check_init
```
**Symbols:**

```
ffffffff810fb280-ffffffff810fb29a: register_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int register_pm_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81107430)
Location: kernel/power/main.c:71
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_pm_sync_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/hung_task.c:hung_task_init
  - kernel/trace/fgraph.c:register_ftrace_graph
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/base/power/trace.c:early_resume_init
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/mmc/core/core.c:mmc_register_pm_notifier
  - arch/x86/power/cpu.c:bsp_pm_check_init
```
**Symbols:**

```
ffffffff81107430-ffffffff8110744a: register_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int register_pm_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81111f30)
Location: kernel/power/main.c:71
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_pm_sync_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/hung_task.c:hung_task_init
  - kernel/trace/fgraph.c:register_ftrace_graph
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/base/power/trace.c:early_resume_init
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/mmc/core/core.c:mmc_register_pm_notifier
  - arch/x86/power/cpu.c:bsp_pm_check_init
```
**Symbols:**

```
ffffffff81111f30-ffffffff81111f4a: register_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int register_pm_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff8110f000)
Location: kernel/power/main.c:71
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_pm_sync_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/hung_task.c:hung_task_init
  - kernel/trace/fgraph.c:register_ftrace_graph
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/base/power/trace.c:early_resume_init
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/mmc/core/core.c:mmc_register_pm_notifier
  - arch/x86/power/cpu.c:bsp_pm_check_init
```
**Symbols:**

```
ffffffff8110f000-ffffffff8110f01a: register_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int register_pm_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff8110faa0)
Location: kernel/power/main.c:71
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_pm_sync_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/hung_task.c:hung_task_init
  - kernel/trace/fgraph.c:register_ftrace_graph
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/base/power/trace.c:early_resume_init
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/thermal/thermal_core.c:thermal_init
  - arch/x86/power/cpu.c:bsp_pm_check_init
```
**Symbols:**

```
ffffffff8110faa0-ffffffff8110faba: register_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int register_pm_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff8112f3f0)
Location: kernel/power/main.c:71
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_pm_sync_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/hung_task.c:hung_task_init
  - kernel/trace/fgraph.c:register_ftrace_graph
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/base/power/trace.c:early_resume_init
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - arch/x86/power/cpu.c:bsp_pm_check_init
```
**Symbols:**

```
ffffffff8112f3f0-ffffffff8112f40a: register_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int register_pm_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81150a50)
Location: kernel/power/main.c:71
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_pm_sync_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/hung_task.c:hung_task_init
  - kernel/trace/fgraph.c:register_ftrace_graph
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/char/random.c:random_init
  - drivers/base/power/trace.c:early_resume_init
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - arch/x86/power/cpu.c:bsp_pm_check_init
```
**Symbols:**

```
ffffffff81150a50-ffffffff81150a72: register_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int register_pm_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff8117f490)
Location: kernel/power/main.c:74
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_pm_sync_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/hung_task.c:hung_task_init
  - kernel/trace/fgraph.c:register_ftrace_graph
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/char/random.c:random_init
  - drivers/char/random.c:random_init
  - drivers/base/power/trace.c:early_resume_init
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - arch/x86/power/cpu.c:bsp_pm_check_init
```
**Symbols:**

```
ffffffff8117f490-ffffffff8117f4b2: register_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int register_pm_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff811901a0)
Location: kernel/power/main.c:102
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_pm_sync_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/hung_task.c:hung_task_init
  - kernel/trace/fgraph.c:register_ftrace_graph
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/char/random.c:random_init
  - drivers/char/random.c:random_init
  - drivers/base/power/trace.c:early_resume_init
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - arch/x86/power/cpu.c:bsp_pm_check_init
```
**Symbols:**

```
ffffffff811901a0-ffffffff811901c2: register_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int register_pm_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff8119eb60)
Location: kernel/power/main.c:86
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_pm_sync_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/hung_task.c:hung_task_init
  - kernel/trace/fgraph.c:register_ftrace_graph
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/char/random.c:random_init
  - drivers/char/random.c:random_init
  - drivers/base/power/trace.c:early_resume_init
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/watchdog/watchdog_core.c:__watchdog_register_device
  - arch/x86/power/cpu.c:bsp_pm_check_init
```
**Symbols:**

```
ffffffff8119eb60-ffffffff8119eb82: register_pm_notifier (STB_GLOBAL)
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
int register_pm_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffff80001016e398)
Location: kernel/power/main.c:71
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_pm_sync_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/hung_task.c:hung_task_init
  - kernel/trace/fgraph.c:register_ftrace_graph
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/mfd/twl6030-irq.c:twl6030_init_irq
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/mmc/core/core.c:mmc_register_pm_notifier
```
**Symbols:**

```
ffff80001016e398-ffff80001016e3cc: register_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int register_pm_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (c03b9188)
Location: kernel/power/main.c:71
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_pm_sync_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/hung_task.c:hung_task_init
  - kernel/trace/fgraph.c:register_ftrace_graph
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/mfd/twl6030-irq.c:twl6030_init_irq
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/mmc/core/core.c:mmc_register_pm_notifier
  - sound/soc/soc-jack.c:snd_soc_jack_add_gpios
```
**Symbols:**

```
c03b9188-c03b91b0: register_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int register_pm_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (c0000000001c5cf0)
Location: kernel/power/main.c:71
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_pm_sync_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/hung_task.c:hung_task_init
  - kernel/trace/fgraph.c:register_ftrace_graph
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/mfd/twl6030-irq.c:twl6030_init_irq
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/mmc/core/core.c:mmc_register_pm_notifier
```
**Symbols:**

```
c0000000001c5cf0-c0000000001c5d30: register_pm_notifier (STB_GLOBAL)
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
Location: include/linux/suspend.h:512
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/suspend.h:512
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/suspend.h:512
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
int register_pm_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81100740)
Location: kernel/power/main.c:71
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_pm_sync_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/hung_task.c:hung_task_init
  - kernel/trace/fgraph.c:register_ftrace_graph
  - drivers/xen/manage.c:xen_setup_pm_notifier
  - drivers/base/power/trace.c:early_resume_init
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/mmc/core/core.c:mmc_register_pm_notifier
  - arch/x86/power/cpu.c:bsp_pm_check_init
```
**Symbols:**

```
ffffffff81100740-ffffffff8110075a: register_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int register_pm_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810f0930)
Location: kernel/power/main.c:71
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_pm_sync_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/hung_task.c:hung_task_init
  - kernel/trace/fgraph.c:register_ftrace_graph
  - drivers/base/power/trace.c:early_resume_init
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/thermal/thermal_core.c:thermal_init
  - arch/x86/power/cpu.c:bsp_pm_check_init
```
**Symbols:**

```
ffffffff810f0930-ffffffff810f094a: register_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int register_pm_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810fd900)
Location: kernel/power/main.c:71
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_pm_sync_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/hung_task.c:hung_task_init
  - kernel/trace/fgraph.c:register_ftrace_graph
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/base/power/trace.c:early_resume_init
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/mmc/core/core.c:mmc_register_pm_notifier
  - arch/x86/power/cpu.c:bsp_pm_check_init
```
**Symbols:**

```
ffffffff810fd900-ffffffff810fd91a: register_pm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int register_pm_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81108bc0)
Location: kernel/power/main.c:71
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_pm_sync_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/hung_task.c:hung_task_init
  - kernel/trace/fgraph.c:register_ftrace_graph
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/base/power/trace.c:early_resume_init
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/mmc/core/core.c:mmc_register_pm_notifier
  - arch/x86/power/cpu.c:bsp_pm_check_init
```
**Symbols:**

```
ffffffff81108bc0-ffffffff81108bda: register_pm_notifier (STB_GLOBAL)
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
