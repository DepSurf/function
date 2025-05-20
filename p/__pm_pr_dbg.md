# Function: <code>__pm_pr_dbg</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __pm_pr_dbg(bool defer, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810dfd60)
Location: kernel/power/main.c:398
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time
  - drivers/base/power/main.c:dpm_show_time
```
**Symbols:**

```
ffffffff810dfd60-ffffffff810dfdf4: __pm_pr_dbg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void __pm_pr_dbg(bool defer, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/main.c (0)
Location: kernel/power/main.c:427
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time
  - drivers/base/power/main.c:dpm_show_time
```
**Symbols:**

```
ffffffff810e8466-ffffffff810e84b2: __pm_pr_dbg.cold.1 (STB_LOCAL)
ffffffff810e8400-ffffffff810e8455: __pm_pr_dbg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void __pm_pr_dbg(bool defer, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/main.c (0)
Location: kernel/power/main.c:416
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time
  - drivers/base/power/main.c:dpm_show_time
```
**Symbols:**

```
ffffffff810f3a76-ffffffff810f3ac2: __pm_pr_dbg.cold.1 (STB_LOCAL)
ffffffff810f3a10-ffffffff810f3a65: __pm_pr_dbg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __pm_pr_dbg(bool defer, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/main.c (0)
Location: kernel/power/main.c:428
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time
  - drivers/base/power/main.c:dpm_show_time
  - drivers/base/power/wakeup.c:pm_wakeup_pending
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
```
**Symbols:**

```
ffffffff810fbf66-ffffffff810fbfb2: __pm_pr_dbg.cold (STB_LOCAL)
ffffffff810fbf00-ffffffff810fbf55: __pm_pr_dbg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void __pm_pr_dbg(bool defer, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/main.c (0)
Location: kernel/power/main.c:514
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
  - drivers/base/power/main.c:dpm_show_time
  - drivers/base/power/wakeup.c:pm_wakeup_pending
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
```
**Symbols:**

```
ffffffff81108386-ffffffff811083d2: __pm_pr_dbg.cold (STB_LOCAL)
ffffffff81108320-ffffffff81108375: __pm_pr_dbg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void __pm_pr_dbg(bool defer, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/main.c (0)
Location: kernel/power/main.c:553
Inline: False
Direct callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
  - drivers/base/power/main.c:dpm_show_time
  - drivers/base/power/wakeup.c:pm_wakeup_pending
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
```
**Symbols:**

```
ffffffff81112f76-ffffffff81112fc2: __pm_pr_dbg.cold (STB_LOCAL)
ffffffff81112f10-ffffffff81112f65: __pm_pr_dbg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void __pm_pr_dbg(bool defer, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/main.c (0)
Location: kernel/power/main.c:553
Inline: False
Direct callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/power/main.c:dpm_show_time
  - drivers/base/power/wakeup.c:pm_wakeup_pending
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
```
**Symbols:**

```
ffffffff81bde8fa-ffffffff81bde946: __pm_pr_dbg.cold (STB_LOCAL)
ffffffff8110ffc0-ffffffff81110015: __pm_pr_dbg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void __pm_pr_dbg(bool defer, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/main.c (0)
Location: kernel/power/main.c:553
Inline: False
Direct callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/power/main.c:dpm_show_time
  - drivers/base/power/wakeup.c:pm_wakeup_pending
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
```
**Symbols:**

```
ffffffff81bd0a73-ffffffff81bd0abf: __pm_pr_dbg.cold (STB_LOCAL)
ffffffff81110a00-ffffffff81110a55: __pm_pr_dbg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __pm_pr_dbg(bool defer, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/main.c (0)
Location: kernel/power/main.c:556
Inline: False
Direct callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/power/main.c:dpm_show_time
  - drivers/base/power/wakeup.c:pm_wakeup_pending
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
```
**Symbols:**

```
ffffffff81ca9744-ffffffff81ca97a4: __pm_pr_dbg.cold (STB_LOCAL)
ffffffff811304b0-ffffffff81130527: __pm_pr_dbg (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __pm_pr_dbg(bool defer, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffff80001016f5a8)
Location: kernel/power/main.c:514
Inline: False
Direct callers:
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/suspend.c:s2idle_loop
  - kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time
  - drivers/base/power/main.c:dpm_show_time
  - drivers/base/power/wakeup.c:pm_wakeup_pending
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
```
**Symbols:**

```
ffff80001016f5a8-ffff80001016f658: __pm_pr_dbg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __pm_pr_dbg(bool defer, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (c03ba204)
Location: kernel/power/main.c:514
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time
  - drivers/base/power/main.c:dpm_show_time
  - drivers/base/power/wakeup.c:pm_wakeup_pending
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
```
**Symbols:**

```
c03ba204-c03ba2a8: __pm_pr_dbg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __pm_pr_dbg(bool defer, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (c0000000001c74b0)
Location: kernel/power/main.c:514
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time
  - drivers/base/power/main.c:dpm_show_time
  - drivers/base/power/wakeup.c:pm_wakeup_pending
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
```
**Symbols:**

```
c0000000001c74b0-c0000000001c757c: __pm_pr_dbg (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void __pm_pr_dbg(bool defer, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/main.c (0)
Location: kernel/power/main.c:514
Inline: False
Direct callers:
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
  - drivers/base/power/main.c:dpm_show_time
  - drivers/base/power/wakeup.c:pm_wakeup_pending
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
```
**Symbols:**

```
ffffffff811014c6-ffffffff81101512: __pm_pr_dbg.cold (STB_LOCAL)
ffffffff81101460-ffffffff811014b5: __pm_pr_dbg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void __pm_pr_dbg(bool defer, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/main.c (0)
Location: kernel/power/main.c:514
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
  - drivers/base/power/main.c:dpm_show_time
  - drivers/base/power/wakeup.c:pm_wakeup_pending
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
```
**Symbols:**

```
ffffffff810f1886-ffffffff810f18d2: __pm_pr_dbg.cold (STB_LOCAL)
ffffffff810f1820-ffffffff810f1875: __pm_pr_dbg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void __pm_pr_dbg(bool defer, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/main.c (0)
Location: kernel/power/main.c:514
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
  - drivers/base/power/main.c:dpm_show_time
  - drivers/base/power/wakeup.c:pm_wakeup_pending
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
```
**Symbols:**

```
ffffffff810fe856-ffffffff810fe8a2: __pm_pr_dbg.cold (STB_LOCAL)
ffffffff810fe7f0-ffffffff810fe845: __pm_pr_dbg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void __pm_pr_dbg(bool defer, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/main.c (0)
Location: kernel/power/main.c:514
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:load_image_and_restore
  - kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
  - drivers/base/power/main.c:dpm_show_time
  - drivers/base/power/wakeup.c:pm_wakeup_pending
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
```
**Symbols:**

```
ffffffff81109b16-ffffffff81109b62: __pm_pr_dbg.cold (STB_LOCAL)
ffffffff81109ab0-ffffffff81109b05: __pm_pr_dbg (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
