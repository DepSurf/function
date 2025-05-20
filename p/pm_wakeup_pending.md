# Function: <code>pm_wakeup_pending</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool pm_wakeup_pending();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff8155c680)
Location: drivers/base/power/wakeup.c:841
Inline: False
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_platform_enter
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend
```
**Symbols:**

```
ffffffff8155c680-ffffffff8155c70f: pm_wakeup_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool pm_wakeup_pending();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815ae940)
Location: drivers/base/power/wakeup.c:839
Inline: False
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
```
**Symbols:**

```
ffffffff815ae940-ffffffff815ae9cf: pm_wakeup_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool pm_wakeup_pending();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815dd740)
Location: drivers/base/power/wakeup.c:839
Inline: False
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
```
**Symbols:**

```
ffffffff815dd740-ffffffff815dd7cf: pm_wakeup_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool pm_wakeup_pending();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815f2370)
Location: drivers/base/power/wakeup.c:840
Inline: False
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
```
**Symbols:**

```
ffffffff815f2370-ffffffff815f2404: pm_wakeup_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool pm_wakeup_pending();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81659910)
Location: drivers/base/power/wakeup.c:841
Inline: False
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
```
**Symbols:**

```
ffffffff81659910-ffffffff816599a4: pm_wakeup_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool pm_wakeup_pending();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81695550)
Location: drivers/base/power/wakeup.c:840
Inline: False
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
```
**Symbols:**

```
ffffffff81695550-ffffffff816955ed: pm_wakeup_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool pm_wakeup_pending();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816b5bc0)
Location: drivers/base/power/wakeup.c:846
Inline: False
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
```
**Symbols:**

```
ffffffff816b5bc0-ffffffff816b5c53: pm_wakeup_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool pm_wakeup_pending();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816efa00)
Location: drivers/base/power/wakeup.c:830
Inline: False
Direct callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend_noirq
```
**Symbols:**

```
ffffffff816efa00-ffffffff816efa8f: pm_wakeup_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool pm_wakeup_pending();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81713a20)
Location: drivers/base/power/wakeup.c:850
Inline: False
Direct callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
```
**Symbols:**

```
ffffffff81713a20-ffffffff81713aaf: pm_wakeup_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool pm_wakeup_pending();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817cf4e0)
Location: drivers/base/power/wakeup.c:909
Inline: False
Direct callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:s2idle_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:create_image
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
```
**Symbols:**

```
ffffffff817cf4e0-ffffffff817cf573: pm_wakeup_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool pm_wakeup_pending();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817e3ae0)
Location: drivers/base/power/wakeup.c:909
Inline: False
Direct callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:s2idle_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:create_image
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
```
**Symbols:**

```
ffffffff817e3ae0-ffffffff817e3b73: pm_wakeup_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool pm_wakeup_pending();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817c7f20)
Location: drivers/base/power/wakeup.c:910
Inline: False
Direct callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:create_image
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
```
**Symbols:**

```
ffffffff817c7f20-ffffffff817c7fb3: pm_wakeup_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool pm_wakeup_pending();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (0)
Location: drivers/base/power/wakeup.c:911
Inline: False
Direct callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:create_image
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
```
**Symbols:**

```
ffffffff81d03f1c-ffffffff81d03f39: pm_wakeup_pending.cold (STB_LOCAL)
ffffffff81852340-ffffffff818523f0: pm_wakeup_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool pm_wakeup_pending();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (0)
Location: drivers/base/power/wakeup.c:911
Inline: False
Direct callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:create_image
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
```
**Symbols:**

```
ffffffff81ecc79b-ffffffff81ecc7dd: pm_wakeup_pending.cold (STB_LOCAL)
ffffffff819972d0-ffffffff819973bd: pm_wakeup_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool pm_wakeup_pending();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (0)
Location: drivers/base/power/wakeup.c:881
Inline: False
Direct callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:create_image
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
```
**Symbols:**

```
ffffffff8209894f-ffffffff82098980: pm_wakeup_pending.cold (STB_LOCAL)
ffffffff81b080b0-ffffffff81b081b5: pm_wakeup_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool pm_wakeup_pending();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (0)
Location: drivers/base/power/wakeup.c:876
Inline: False
Direct callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:create_image
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
```
**Symbols:**

```
ffffffff82119930-ffffffff8211994c: pm_wakeup_pending.cold (STB_LOCAL)
ffffffff81b56100-ffffffff81b561e9: pm_wakeup_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool pm_wakeup_pending();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (0)
Location: drivers/base/power/wakeup.c:876
Inline: False
Direct callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:create_image
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
```
**Symbols:**

```
ffffffff821f78f2-ffffffff821f790e: pm_wakeup_pending.cold (STB_LOCAL)
ffffffff81bae6c0-ffffffff81bae7a9: pm_wakeup_pending (STB_GLOBAL)
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
bool pm_wakeup_pending();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffff800010904f50)
Location: drivers/base/power/wakeup.c:850
Inline: False
Direct callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/suspend.c:s2idle_loop
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
```
**Symbols:**

```
ffff800010904f50-ffff800010905068: pm_wakeup_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool pm_wakeup_pending();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (c09eeddc)
Location: drivers/base/power/wakeup.c:850
Inline: False
Direct callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
```
**Symbols:**

```
c09eeddc-c09eee8c: pm_wakeup_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool pm_wakeup_pending();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (c0000000009a3a30)
Location: drivers/base/power/wakeup.c:850
Inline: False
Direct callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
```
**Symbols:**

```
c0000000009a3a30-c0000000009a3b38: pm_wakeup_pending (STB_GLOBAL)
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
In kernel/power/process.c (0)
Location: include/linux/suspend.h:526
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
bool pm_wakeup_pending();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816d9d50)
Location: drivers/base/power/wakeup.c:850
Inline: False
Direct callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
```
**Symbols:**

```
ffffffff816d9d50-ffffffff816d9ddf: pm_wakeup_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool pm_wakeup_pending();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816b43d0)
Location: drivers/base/power/wakeup.c:850
Inline: False
Direct callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
```
**Symbols:**

```
ffffffff816b43d0-ffffffff816b445f: pm_wakeup_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool pm_wakeup_pending();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817076e0)
Location: drivers/base/power/wakeup.c:850
Inline: False
Direct callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
```
**Symbols:**

```
ffffffff817076e0-ffffffff8170776f: pm_wakeup_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool pm_wakeup_pending();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81722110)
Location: drivers/base/power/wakeup.c:850
Inline: False
Direct callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
```
**Symbols:**

```
ffffffff81722110-ffffffff8172219f: pm_wakeup_pending (STB_GLOBAL)
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
