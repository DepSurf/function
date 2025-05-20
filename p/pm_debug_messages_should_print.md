# Function: <code>pm_debug_messages_should_print</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool pm_debug_messages_should_print();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/main.c (0)
Location: kernel/power/main.c:586
Inline: False
Direct callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:find_resume_device
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time
  - drivers/pinctrl/pinctrl-amd.c:do_amd_gpio_irq_handler
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/power/main.c:dpm_show_time
  - drivers/base/power/wakeup.c:pm_system_irq_wakeup
  - drivers/base/power/wakeup.c:pm_system_irq_wakeup
  - drivers/base/power/wakeup.c:pm_wakeup_pending
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
```
**Symbols:**

```
ffffffff820d6bd9-ffffffff820d6c0f: pm_debug_messages_should_print.cold (STB_LOCAL)
ffffffff81191570-ffffffff811915aa: pm_debug_messages_should_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool pm_debug_messages_should_print();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/main.c (0)
Location: kernel/power/main.c:570
Inline: False
Direct callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:find_resume_device
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_suspend
  - drivers/pinctrl/pinctrl-amd.c:do_amd_gpio_irq_handler
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/power/main.c:dpm_show_time
  - drivers/base/power/wakeup.c:pm_system_irq_wakeup
  - drivers/base/power/wakeup.c:pm_system_irq_wakeup
  - drivers/base/power/wakeup.c:pm_wakeup_pending
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
```
**Symbols:**

```
ffffffff821b1e6f-ffffffff821b1ea5: pm_debug_messages_should_print.cold (STB_LOCAL)
ffffffff8119ff30-ffffffff8119ff6a: pm_debug_messages_should_print (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
