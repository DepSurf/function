# Function: <code>trace_suspend_resume</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void trace_suspend_resume(const char *action, int val, bool start);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (ffffffff81081be1)
Location: include/trace/events/power.h:195
Inline: True
Inline callers:
  - kernel/cpu.c:disable_nonboot_cpus
  - kernel/cpu.c:disable_nonboot_cpus
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:enable_nonboot_cpus
```
```
In kernel/power/process.c (ffffffff810cdbf9)
Location: include/trace/events/power.h:195
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/suspend.c (ffffffff810ce160)
Location: include/trace/events/power.h:195
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:pm_suspend
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/suspend.c:pm_suspend
```
```
In kernel/power/hibernate.c (ffffffff810cf320)
Location: include/trace/events/power.h:195
Inline: True
Direct callers:
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
```
```
In kernel/time/tick-common.c (ffffffff810fcbfe)
Location: include/trace/events/power.h:195
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_freeze
  - kernel/time/tick-common.c:tick_unfreeze
```
```
In drivers/acpi/sleep.c (ffffffff8147b94b)
Location: include/trace/events/power.h:195
Inline: True
Direct callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/base/syscore.c (ffffffff8154c28c)
Location: include/trace/events/power.h:195
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/power/main.c (ffffffff81559e6d)
Location: include/trace/events/power.h:195
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
```
**Symbols:**

```
ffffffff810ce160-ffffffff810ce1ca: trace_suspend_resume (STB_LOCAL)
ffffffff810cf320-ffffffff810cf385: trace_suspend_resume.constprop.8 (STB_LOCAL)
ffffffff8147b94b-ffffffff8147b9af: trace_suspend_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void trace_suspend_resume(const char *action, int val, bool start);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (ffffffff81084f26)
Location: include/trace/events/power.h:195
Inline: True
Inline callers:
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:disable_nonboot_cpus
  - kernel/cpu.c:disable_nonboot_cpus
```
```
In kernel/power/process.c (ffffffff810d273b)
Location: include/trace/events/power.h:195
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/suspend.c (ffffffff810d3521)
Location: include/trace/events/power.h:195
Inline: True
Inline callers:
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
Direct callers:
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
```
```
In kernel/power/hibernate.c (ffffffff810d3dc0)
Location: include/trace/events/power.h:195
Inline: True
Direct callers:
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
```
```
In kernel/time/tick-common.c (ffffffff81104031)
Location: include/trace/events/power.h:195
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In drivers/acpi/sleep.c (ffffffff814c9f6e)
Location: include/trace/events/power.h:195
Inline: True
Direct callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/base/syscore.c (ffffffff8159e07c)
Location: include/trace/events/power.h:195
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/power/main.c (ffffffff815ad409)
Location: include/trace/events/power.h:195
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_resume_noirq
```
**Symbols:**

```
ffffffff810d2cc0-ffffffff810d2d23: trace_suspend_resume (STB_LOCAL)
ffffffff810d3dc0-ffffffff810d3e1e: trace_suspend_resume.constprop.7 (STB_LOCAL)
ffffffff814c9f6e-ffffffff814c9fcb: trace_suspend_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void trace_suspend_resume(const char *action, int val, bool start);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (ffffffff81089ec2)
Location: include/trace/events/power.h:200
Inline: True
Inline callers:
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
```
```
In kernel/power/process.c (ffffffff810d92eb)
Location: include/trace/events/power.h:200
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/suspend.c (ffffffff810da0b1)
Location: include/trace/events/power.h:200
Inline: True
Inline callers:
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
Direct callers:
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
```
```
In kernel/power/hibernate.c (ffffffff810da950)
Location: include/trace/events/power.h:200
Inline: True
Direct callers:
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
```
```
In kernel/time/tick-common.c (ffffffff8110b732)
Location: include/trace/events/power.h:200
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In drivers/acpi/sleep.c (ffffffff814ebec9)
Location: include/trace/events/power.h:200
Inline: True
Direct callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/base/syscore.c (ffffffff815cc62c)
Location: include/trace/events/power.h:200
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/power/main.c (ffffffff815dc1c9)
Location: include/trace/events/power.h:200
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_resume_noirq
```
**Symbols:**

```
ffffffff810d9850-ffffffff810d98b3: trace_suspend_resume (STB_LOCAL)
ffffffff810da950-ffffffff810da9ae: trace_suspend_resume.constprop.7 (STB_LOCAL)
ffffffff814ebec9-ffffffff814ebf26: trace_suspend_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void trace_suspend_resume(const char *action, int val, bool start);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (ffffffff81086d81)
Location: include/trace/events/power.h:200
Inline: True
Inline callers:
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
```
```
In kernel/power/process.c (ffffffff810d82d9)
Location: include/trace/events/power.h:200
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/suspend.c (ffffffff810d9190)
Location: include/trace/events/power.h:200
Inline: True
Inline callers:
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
Direct callers:
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/suspend.c:pm_suspend
```
```
In kernel/power/hibernate.c (ffffffff810d9a30)
Location: include/trace/events/power.h:200
Inline: True
Direct callers:
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
```
```
In kernel/time/tick-common.c (ffffffff8110d622)
Location: include/trace/events/power.h:200
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In drivers/acpi/sleep.c (ffffffff814f8813)
Location: include/trace/events/power.h:200
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/base/syscore.c (ffffffff815e11cc)
Location: include/trace/events/power.h:200
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/power/main.c (ffffffff815f0d49)
Location: include/trace/events/power.h:200
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_resume_noirq
```
**Symbols:**

```
ffffffff810d8830-ffffffff810d8893: trace_suspend_resume (STB_LOCAL)
ffffffff810d9a30-ffffffff810d9a8e: trace_suspend_resume.constprop.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void trace_suspend_resume(const char *action, int val, bool start);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108db1b)
Location: include/trace/events/power.h:201
Inline: True
Inline callers:
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
```
```
In kernel/power/process.c (ffffffff810e03c9)
Location: include/trace/events/power.h:201
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/suspend.c (ffffffff810e0e13)
Location: include/trace/events/power.h:201
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
```
```
In kernel/power/hibernate.c (ffffffff810e2090)
Location: include/trace/events/power.h:201
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
```
```
In kernel/time/tick-common.c (ffffffff811188a2)
Location: include/trace/events/power.h:201
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In drivers/acpi/sleep.c (ffffffff81539ef3)
Location: include/trace/events/power.h:201
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/base/syscore.c (ffffffff816482ec)
Location: include/trace/events/power.h:201
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/power/main.c (ffffffff81658299)
Location: include/trace/events/power.h:201
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_noirq_resume_devices
```
**Symbols:**

```
ffffffff810e0920-ffffffff810e098c: trace_suspend_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void trace_suspend_resume(const char *action, int val, bool start);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810917ef)
Location: include/trace/events/power.h:201
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
Direct callers:
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:enable_nonboot_cpus
```
```
In kernel/power/process.c (ffffffff810e8968)
Location: include/trace/events/power.h:201
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/suspend.c (ffffffff810e9508)
Location: include/trace/events/power.h:201
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
```
```
In kernel/power/hibernate.c (ffffffff810ea391)
Location: include/trace/events/power.h:201
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
```
```
In kernel/time/tick-common.c (ffffffff8112544c)
Location: include/trace/events/power.h:201
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In drivers/acpi/sleep.c (ffffffff8156fca2)
Location: include/trace/events/power.h:201
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/base/syscore.c (ffffffff816838b5)
Location: include/trace/events/power.h:201
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/power/main.c (ffffffff81693c95)
Location: include/trace/events/power.h:201
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_noirq_resume_devices
```
**Symbols:**

```
ffffffff8108f870-ffffffff8108f8dc: trace_suspend_resume (STB_LOCAL)
ffffffff810e8f30-ffffffff810e8f9c: trace_suspend_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void trace_suspend_resume(const char *action, int val, bool start);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81099acf)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
Direct callers:
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:enable_nonboot_cpus
```
```
In kernel/power/process.c (ffffffff810f3f78)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/suspend.c (ffffffff810f4b28)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
```
```
In kernel/power/hibernate.c (ffffffff810f59c1)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
```
```
In kernel/time/tick-common.c (ffffffff81130b3c)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In drivers/acpi/sleep.c (ffffffff81587862)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/base/syscore.c (ffffffff816a3585)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/power/main.c (ffffffff816b4315)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_noirq_resume_devices
```
**Symbols:**

```
ffffffff81097b70-ffffffff81097bdc: trace_suspend_resume (STB_LOCAL)
ffffffff810f4550-ffffffff810f45bc: trace_suspend_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void trace_suspend_resume(const char *action, int val, bool start);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109e0ce)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
Direct callers:
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:enable_nonboot_cpus
```
```
In kernel/power/process.c (ffffffff810fc378)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/suspend.c (ffffffff810fd250)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/power/hibernate.c (ffffffff810fdfd5)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
```
```
In kernel/time/tick-common.c (ffffffff8113b68f)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In drivers/acpi/sleep.c (ffffffff815b8652)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/base/syscore.c (ffffffff816dc495)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/power/main.c (ffffffff816ee1b5)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_noirq_resume_devices
```
**Symbols:**

```
ffffffff8109c140-ffffffff8109c1a5: trace_suspend_resume (STB_LOCAL)
ffffffff810fcac0-ffffffff810fcb25: trace_suspend_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void trace_suspend_resume(const char *action, int val, bool start);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a4639)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
Direct callers:
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:enable_nonboot_cpus
```
```
In kernel/power/process.c (ffffffff81108798)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/suspend.c (ffffffff81109670)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/power/hibernate.c (ffffffff8110a405)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
```
```
In kernel/time/tick-common.c (ffffffff811472a0)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In drivers/acpi/sleep.c (ffffffff815d98c2)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/base/syscore.c (ffffffff81700525)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/power/main.c (ffffffff81712195)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_resume_noirq
```
**Symbols:**

```
ffffffff810a26c0-ffffffff810a2725: trace_suspend_resume (STB_LOCAL)
ffffffff81108eb0-ffffffff81108f15: trace_suspend_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void trace_suspend_resume(const char *action, int val, bool start);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810ab941)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
Direct callers:
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:thaw_secondary_cpus
```
```
In kernel/power/process.c (ffffffff81113398)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/suspend.c (ffffffff811142a0)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:s2idle_enter
  - kernel/power/suspend.c:s2idle_enter
  - kernel/power/suspend.c:s2idle_enter
  - kernel/power/suspend.c:s2idle_enter
Direct callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:suspend_prepare
  - kernel/power/suspend.c:suspend_prepare
```
```
In kernel/power/hibernate.c (ffffffff81114e3b)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/power/hibernate.c:create_image
  - kernel/power/hibernate.c:create_image
  - kernel/power/hibernate.c:create_image
  - kernel/power/hibernate.c:create_image
```
```
In kernel/time/tick-common.c (ffffffff81157125)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In drivers/acpi/sleep.c (ffffffff81683763)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/base/syscore.c (ffffffff817ba615)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/power/main.c (ffffffff817cdb45)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_noirq_resume_devices
```
**Symbols:**

```
ffffffff810a9650-ffffffff810a96b5: trace_suspend_resume (STB_LOCAL)
ffffffff81113a40-ffffffff81113aa5: trace_suspend_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void trace_suspend_resume(const char *action, int val, bool start);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81bdb5bf)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
Direct callers:
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:thaw_secondary_cpus
```
```
In kernel/power/process.c (ffffffff811103e8)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/suspend.c (ffffffff81110f08)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:s2idle_enter
  - kernel/power/suspend.c:s2idle_enter
  - kernel/power/suspend.c:s2idle_enter
  - kernel/power/suspend.c:s2idle_enter
Direct callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:suspend_prepare
  - kernel/power/suspend.c:suspend_prepare
```
```
In kernel/power/hibernate.c (ffffffff81111843)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/power/hibernate.c:create_image
  - kernel/power/hibernate.c:create_image
  - kernel/power/hibernate.c:create_image
  - kernel/power/hibernate.c:create_image
```
```
In kernel/time/tick-common.c (ffffffff8115320a)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In drivers/acpi/sleep.c (ffffffff816a168e)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/base/syscore.c (ffffffff817cf2f5)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/power/main.c (ffffffff817e24ae)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_noirq_resume_devices
```
**Symbols:**

```
ffffffff810a50a0-ffffffff810a50e1: trace_suspend_resume (STB_LOCAL)
ffffffff81110730-ffffffff81110771: trace_suspend_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void trace_suspend_resume(const char *action, int val, bool start);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81bcd6b1)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
Direct callers:
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:thaw_secondary_cpus
```
```
In kernel/power/process.c (ffffffff81110e28)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/suspend.c (ffffffff81111968)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/suspend.c:s2idle_loop
Direct callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
```
```
In kernel/power/hibernate.c (ffffffff81112293)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/power/hibernate.c:create_image
  - kernel/power/hibernate.c:create_image
  - kernel/power/hibernate.c:create_image
  - kernel/power/hibernate.c:create_image
```
```
In kernel/time/tick-common.c (ffffffff8115460a)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In drivers/acpi/sleep.c (ffffffff8168450e)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/base/syscore.c (ffffffff817b2d05)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/power/main.c (ffffffff817c688e)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_noirq_resume_devices
```
**Symbols:**

```
ffffffff810a5c20-ffffffff810a5c61: trace_suspend_resume (STB_LOCAL)
ffffffff81111170-ffffffff811111b1: trace_suspend_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void trace_suspend_resume(const char *action, int val, bool start);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81ca3ff2)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
Direct callers:
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:thaw_secondary_cpus
```
```
In kernel/power/process.c (ffffffff81130908)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/suspend.c (ffffffff811314d2)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/suspend.c:s2idle_loop
```
```
In kernel/power/hibernate.c (ffffffff811322c3)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/power/hibernate.c:create_image
  - kernel/power/hibernate.c:create_image
  - kernel/power/hibernate.c:create_image
  - kernel/power/hibernate.c:create_image
```
```
In kernel/time/tick-common.c (ffffffff81178e2a)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In drivers/acpi/sleep.c (ffffffff816f97ae)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/base/syscore.c (ffffffff8183c1c5)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/power/main.c (ffffffff81850c40)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_noirq_resume_devices
```
**Symbols:**

```
ffffffff810b75b0-ffffffff810b75ee: trace_suspend_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void trace_suspend_resume(const char *action, int val, bool start);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81e5386e)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
Direct callers:
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:thaw_secondary_cpus
```
```
In kernel/power/process.c (ffffffff81152178)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/suspend.c (ffffffff81152f00)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/suspend.c:s2idle_loop
```
```
In kernel/power/hibernate.c (ffffffff81153fae)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/power/hibernate.c:create_image
  - kernel/power/hibernate.c:create_image
  - kernel/power/hibernate.c:create_image
  - kernel/power/hibernate.c:create_image
```
```
In kernel/time/tick-common.c (ffffffff811ae106)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In drivers/acpi/sleep.c (ffffffff81826b77)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/base/syscore.c (ffffffff8197e7c5)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/power/main.c (ffffffff819966b0)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_noirq_resume_devices
```
**Symbols:**

```
ffffffff810cdee0-ffffffff810cdf6c: trace_suspend_resume (STB_LOCAL)
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
In kernel/cpu.c (ffffffff810ee7f5)
Location: include/trace/events/power.h:248
Inline: True
Inline callers:
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
```
```
In kernel/power/process.c (ffffffff811811d0)
Location: include/trace/events/power.h:248
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/suspend.c (ffffffff811822e8)
Location: include/trace/events/power.h:248
Inline: True
Inline callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/suspend.c:s2idle_loop
```
```
In kernel/power/hibernate.c (ffffffff81183701)
Location: include/trace/events/power.h:248
Inline: True
Inline callers:
  - kernel/power/hibernate.c:create_image
  - kernel/power/hibernate.c:create_image
  - kernel/power/hibernate.c:create_image
  - kernel/power/hibernate.c:create_image
```
```
In kernel/time/tick-common.c (ffffffff811ee7bd)
Location: include/trace/events/power.h:248
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In drivers/acpi/sleep.c (ffffffff819589ee)
Location: include/trace/events/power.h:248
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/base/syscore.c (ffffffff81aebda3)
Location: include/trace/events/power.h:248
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/power/main.c (ffffffff81b073ba)
Location: include/trace/events/power.h:248
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_noirq_resume_devices
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
In kernel/cpu.c (ffffffff810fa7d5)
Location: include/trace/events/power.h:248
Inline: True
Inline callers:
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
```
```
In kernel/power/process.c (ffffffff811920d0)
Location: include/trace/events/power.h:248
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/suspend.c (ffffffff811931c8)
Location: include/trace/events/power.h:248
Inline: True
Inline callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/suspend.c:s2idle_loop
```
```
In kernel/power/hibernate.c (ffffffff81194571)
Location: include/trace/events/power.h:248
Inline: True
Inline callers:
  - kernel/power/hibernate.c:create_image
  - kernel/power/hibernate.c:create_image
  - kernel/power/hibernate.c:create_image
  - kernel/power/hibernate.c:create_image
```
```
In kernel/time/tick-common.c (ffffffff81202eed)
Location: include/trace/events/power.h:248
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In drivers/acpi/sleep.c (ffffffff8199ee6e)
Location: include/trace/events/power.h:248
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/base/syscore.c (ffffffff81b39fe3)
Location: include/trace/events/power.h:248
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/power/main.c (ffffffff81b5540a)
Location: include/trace/events/power.h:248
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_noirq_resume_devices
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
In kernel/cpu.c (ffffffff81103bf5)
Location: include/trace/events/power.h:248
Inline: True
Inline callers:
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
```
```
In kernel/power/process.c (ffffffff811a0ac0)
Location: include/trace/events/power.h:248
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/suspend.c (ffffffff811a1bb8)
Location: include/trace/events/power.h:248
Inline: True
Inline callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/suspend.c:s2idle_loop
```
```
In kernel/power/hibernate.c (ffffffff811a2f61)
Location: include/trace/events/power.h:248
Inline: True
Inline callers:
  - kernel/power/hibernate.c:create_image
  - kernel/power/hibernate.c:create_image
  - kernel/power/hibernate.c:create_image
  - kernel/power/hibernate.c:create_image
```
```
In kernel/time/tick-common.c (ffffffff812194ad)
Location: include/trace/events/power.h:248
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In drivers/acpi/sleep.c (ffffffff819e750e)
Location: include/trace/events/power.h:248
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/base/syscore.c (ffffffff81b91aa3)
Location: include/trace/events/power.h:248
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/power/main.c (ffffffff81bad9ca)
Location: include/trace/events/power.h:248
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_noirq_resume_devices
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void trace_suspend_resume(const char *action, int val, bool start);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffff8000100f9bc0)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
Direct callers:
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:enable_nonboot_cpus
```
```
In kernel/power/process.c (ffff80001016fd50)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/suspend.c (ffff800010170e90)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/suspend.c:s2idle_loop
```
```
In kernel/time/tick-common.c (ffff8000101b22e8)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In drivers/base/syscore.c (ffff8000108eb7f4)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/power/main.c (ffff800010902be0)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_resume_noirq
```
**Symbols:**

```
ffff8000100f7f88-ffff8000100f8024: trace_suspend_resume (STB_LOCAL)
ffff800010170430-ffff8000101704cc: trace_suspend_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void trace_suspend_resume(const char *action, int val, bool start);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c0357e10)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
Direct callers:
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:enable_nonboot_cpus
```
```
In kernel/power/process.c (c03ba9f8)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/suspend.c (c03bb658)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
```
```
In kernel/power/hibernate.c (c03bc9d4)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
```
```
In kernel/time/tick-common.c (c03fc9b0)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In drivers/base/syscore.c (c09d97f0)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/power/main.c (c09ecf68)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_resume_noirq
```
**Symbols:**

```
c0355ba4-c0355c40: trace_suspend_resume (STB_LOCAL)
c03bb07c-c03bb118: trace_suspend_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void trace_suspend_resume(const char *action, int val, bool start);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c000000000140bb4)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
Direct callers:
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:enable_nonboot_cpus
```
```
In kernel/power/process.c (c0000000001c7eb8)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/suspend.c (c0000000001c8f78)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
```
```
In kernel/time/tick-common.c (c000000000217728)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In drivers/base/syscore.c (c000000000982ef8)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/power/main.c (c0000000009a1144)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_resume_noirq
```
**Symbols:**

```
c00000000013e040-c00000000013e10c: trace_suspend_resume (STB_LOCAL)
c0000000001c86c0-c0000000001c878c: trace_suspend_resume (STB_LOCAL)
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
In kernel/power/process.c (ffffffe00010d7d4)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void trace_suspend_resume(const char *action, int val, bool start);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109df59)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
Direct callers:
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:enable_nonboot_cpus
```
```
In kernel/power/process.c (ffffffff811018d8)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/hibernate.c (ffffffff8110265b)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
```
```
In drivers/base/syscore.c (ffffffff816c5d15)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/power/main.c (ffffffff816d8515)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_resume_noirq
```
**Symbols:**

```
ffffffff8109bfe0-ffffffff8109c045: trace_suspend_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void trace_suspend_resume(const char *action, int val, bool start);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108c979)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
Direct callers:
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:enable_nonboot_cpus
```
```
In kernel/power/process.c (ffffffff810f1c98)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/suspend.c (ffffffff810f296a)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
```
```
In kernel/power/hibernate.c (ffffffff810f38e9)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
```
```
In kernel/time/tick-common.c (ffffffff81132640)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In drivers/acpi/sleep.c (ffffffff815b5c2d)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/base/syscore.c (ffffffff816a0f95)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/power/main.c (ffffffff816b2b75)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_resume_noirq
```
**Symbols:**

```
ffffffff8108aa10-ffffffff8108aa75: trace_suspend_resume (STB_LOCAL)
ffffffff810f23b0-ffffffff810f2415: trace_suspend_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void trace_suspend_resume(const char *action, int val, bool start);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109df09)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
Direct callers:
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:enable_nonboot_cpus
```
```
In kernel/power/process.c (ffffffff810fec68)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/suspend.c (ffffffff810ffb40)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/power/hibernate.c (ffffffff811008d5)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
```
```
In kernel/time/tick-common.c (ffffffff8113d770)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In drivers/acpi/sleep.c (ffffffff815cdba2)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/base/syscore.c (ffffffff816f41e5)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/power/main.c (ffffffff81705e55)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_resume_noirq
```
**Symbols:**

```
ffffffff8109bf90-ffffffff8109bff5: trace_suspend_resume (STB_LOCAL)
ffffffff810ff380-ffffffff810ff3e5: trace_suspend_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void trace_suspend_resume(const char *action, int val, bool start);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a5e0e)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
Direct callers:
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:enable_nonboot_cpus
```
```
In kernel/power/process.c (ffffffff81109f38)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/suspend.c (ffffffff8110aeb0)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/power/hibernate.c (ffffffff8110bc75)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
```
```
In kernel/time/tick-common.c (ffffffff8114a26e)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In drivers/acpi/sleep.c (ffffffff815e7a42)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/base/syscore.c (ffffffff8170ea15)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/power/main.c (ffffffff81720825)
Location: include/trace/events/power.h:226
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_resume_noirq
```
**Symbols:**

```
ffffffff810a3b90-ffffffff810a3c0c: trace_suspend_resume (STB_LOCAL)
ffffffff8110a680-ffffffff8110a6fc: trace_suspend_resume (STB_LOCAL)
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
