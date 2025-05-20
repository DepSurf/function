# Function: <code>lock_system_sleep</code>

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
In kernel/power/main.c (ffffffff810cd1c3)
Location: include/linux/suspend.h:437
Inline: True
Inline callers:
  - kernel/power/main.c:pm_test_store
```
```
In kernel/power/suspend.c (ffffffff810ce026)
Location: include/linux/suspend.h:437
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:freeze_set_ops
```
```
In kernel/power/hibernate.c (ffffffff810cefef)
Location: include/linux/suspend.h:437
Inline: True
Inline callers:
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:hibernate
```
```
In kernel/power/user.c (ffffffff810d54f6)
Location: include/linux/suspend.h:437
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_release
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_write
  - kernel/power/user.c:snapshot_read
```
```
In kernel/kexec_core.c (ffffffff8110daec)
Location: include/linux/suspend.h:437
Inline: True
Inline callers:
  - kernel/kexec_core.c:kernel_kexec
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
In kernel/power/main.c (ffffffff810d1c63)
Location: include/linux/suspend.h:436
Inline: True
Inline callers:
  - kernel/power/main.c:pm_test_store
```
```
In kernel/power/suspend.c (ffffffff810d2b86)
Location: include/linux/suspend.h:436
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:freeze_set_ops
```
```
In kernel/power/hibernate.c (ffffffff810d47dc)
Location: include/linux/suspend.h:436
Inline: True
Inline callers:
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate
```
```
In kernel/power/user.c (ffffffff810da608)
Location: include/linux/suspend.h:436
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_write
  - kernel/power/user.c:snapshot_read
  - kernel/power/user.c:snapshot_release
  - kernel/power/user.c:snapshot_open
```
```
In kernel/kexec_core.c (ffffffff8111558c)
Location: include/linux/suspend.h:436
Inline: True
Inline callers:
  - kernel/kexec_core.c:kernel_kexec
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
In kernel/power/main.c (ffffffff810d8803)
Location: include/linux/suspend.h:438
Inline: True
Inline callers:
  - kernel/power/main.c:pm_test_store
```
```
In kernel/power/suspend.c (ffffffff810d9716)
Location: include/linux/suspend.h:438
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:freeze_set_ops
```
```
In kernel/power/hibernate.c (ffffffff810db38c)
Location: include/linux/suspend.h:438
Inline: True
Inline callers:
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate
```
```
In kernel/power/user.c (ffffffff810e10d8)
Location: include/linux/suspend.h:438
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_write
  - kernel/power/user.c:snapshot_read
  - kernel/power/user.c:snapshot_release
  - kernel/power/user.c:snapshot_open
```
```
In kernel/kexec_core.c (ffffffff8111ccac)
Location: include/linux/suspend.h:438
Inline: True
Inline callers:
  - kernel/kexec_core.c:kernel_kexec
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
In kernel/power/main.c (ffffffff810d7803)
Location: include/linux/suspend.h:441
Inline: True
Inline callers:
  - kernel/power/main.c:pm_test_store
```
```
In kernel/power/suspend.c (ffffffff810d86f6)
Location: include/linux/suspend.h:441
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:freeze_set_ops
```
```
In kernel/power/hibernate.c (ffffffff810da47d)
Location: include/linux/suspend.h:441
Inline: True
Inline callers:
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernation_set_ops
```
```
In kernel/power/user.c (ffffffff810e07b8)
Location: include/linux/suspend.h:441
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_write
  - kernel/power/user.c:snapshot_read
  - kernel/power/user.c:snapshot_release
  - kernel/power/user.c:snapshot_open
```
```
In kernel/kexec_core.c (ffffffff8111e8dc)
Location: include/linux/suspend.h:441
Inline: True
Inline callers:
  - kernel/kexec_core.c:kernel_kexec
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
In kernel/power/main.c (ffffffff810df853)
Location: include/linux/suspend.h:446
Inline: True
Inline callers:
  - kernel/power/main.c:pm_test_store
```
```
In kernel/power/suspend.c (ffffffff810e07e6)
Location: include/linux/suspend.h:446
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:s2idle_set_ops
```
```
In kernel/power/hibernate.c (ffffffff810e260d)
Location: include/linux/suspend.h:446
Inline: True
Inline callers:
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernation_set_ops
```
```
In kernel/power/user.c (ffffffff810e8a88)
Location: include/linux/suspend.h:446
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_write
  - kernel/power/user.c:snapshot_read
  - kernel/power/user.c:snapshot_release
  - kernel/power/user.c:snapshot_open
```
```
In kernel/kexec_core.c (ffffffff8112a03c)
Location: include/linux/suspend.h:446
Inline: True
Inline callers:
  - kernel/kexec_core.c:kernel_kexec
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void lock_system_sleep();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810e7e63)
Location: kernel/power/main.c:25
Inline: True
Inline callers:
  - kernel/power/main.c:pm_test_store
Direct callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:s2idle_set_ops
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernation_set_ops
  - kernel/power/hibernate.c:hibernation_set_ops
  - kernel/power/user.c:snapshot_write
  - kernel/power/user.c:snapshot_read
  - kernel/power/user.c:snapshot_release
  - kernel/power/user.c:snapshot_open
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff810e7750-ffffffff810e7777: lock_system_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void lock_system_sleep();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810f3473)
Location: kernel/power/main.c:24
Inline: True
Inline callers:
  - kernel/power/main.c:pm_test_store
Direct callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:s2idle_set_ops
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernation_set_ops
  - kernel/power/hibernate.c:hibernation_set_ops
  - kernel/power/user.c:snapshot_write
  - kernel/power/user.c:snapshot_read
  - kernel/power/user.c:snapshot_release
  - kernel/power/user.c:snapshot_open
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff810f2d50-ffffffff810f2d77: lock_system_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void lock_system_sleep();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810fb933)
Location: kernel/power/main.c:23
Inline: True
Inline callers:
  - kernel/power/main.c:pm_test_store
Direct callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:s2idle_set_ops
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernation_set_ops
  - kernel/power/hibernate.c:hibernation_set_ops
  - kernel/power/user.c:snapshot_write
  - kernel/power/user.c:snapshot_read
  - kernel/power/user.c:snapshot_release
  - kernel/power/user.c:snapshot_open
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff810fb220-ffffffff810fb247: lock_system_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void lock_system_sleep();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81107da3)
Location: kernel/power/main.c:24
Inline: True
Inline callers:
  - kernel/power/main.c:pm_test_store
Direct callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:s2idle_set_ops
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_write
  - kernel/power/user.c:snapshot_read
  - kernel/power/user.c:snapshot_release
  - kernel/power/user.c:snapshot_open
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff81107350-ffffffff81107377: lock_system_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void lock_system_sleep();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81112de3)
Location: kernel/power/main.c:24
Inline: True
Inline callers:
  - kernel/power/main.c:pm_test_store
Direct callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:s2idle_set_ops
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernation_set_ops
  - kernel/power/hibernate.c:hibernation_set_ops
  - kernel/power/user.c:snapshot_write
  - kernel/power/user.c:snapshot_read
  - kernel/power/user.c:snapshot_release
  - kernel/power/user.c:snapshot_open
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff81111e50-ffffffff81111e77: lock_system_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void lock_system_sleep();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff8110feb3)
Location: kernel/power/main.c:24
Inline: True
Inline callers:
  - kernel/power/main.c:pm_test_store
Direct callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:s2idle_set_ops
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernation_set_ops
  - kernel/power/hibernate.c:hibernation_set_ops
  - kernel/power/user.c:snapshot_write
  - kernel/power/user.c:snapshot_read
  - kernel/power/user.c:snapshot_release
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff8110ef20-ffffffff8110ef47: lock_system_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void lock_system_sleep();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff811108f3)
Location: kernel/power/main.c:24
Inline: True
Inline callers:
  - kernel/power/main.c:pm_test_store
Direct callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:s2idle_set_ops
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernation_set_ops
  - kernel/power/hibernate.c:hibernation_set_ops
  - kernel/power/user.c:snapshot_write
  - kernel/power/user.c:snapshot_read
  - kernel/power/user.c:snapshot_release
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff8110f9c0-ffffffff8110f9e7: lock_system_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void lock_system_sleep();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff811303a3)
Location: kernel/power/main.c:24
Inline: True
Inline callers:
  - kernel/power/main.c:pm_test_store
Direct callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:s2idle_set_ops
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernation_set_ops
  - kernel/power/hibernate.c:hibernation_set_ops
  - kernel/power/user.c:snapshot_write
  - kernel/power/user.c:snapshot_read
  - kernel/power/user.c:snapshot_release
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff8112f310-ffffffff8112f337: lock_system_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void lock_system_sleep();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81151bbc)
Location: kernel/power/main.c:24
Inline: True
Inline callers:
  - kernel/power/main.c:pm_test_store
Direct callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:s2idle_set_ops
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernation_set_ops
  - kernel/power/hibernate.c:hibernation_set_ops
  - kernel/power/user.c:snapshot_write
  - kernel/power/user.c:snapshot_read
  - kernel/power/user.c:snapshot_release
  - kernel/power/user.c:snapshot_open
  - drivers/acpi/x86/s2idle.c:acpi_register_lps0_dev
```
**Symbols:**

```
ffffffff81150960-ffffffff8115098f: lock_system_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
unsigned int lock_system_sleep();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81180900)
Location: kernel/power/main.c:24
Inline: True
Inline callers:
  - kernel/power/main.c:pm_test_store
Direct callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:s2idle_set_ops
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernation_set_ops
  - kernel/power/hibernate.c:hibernation_set_ops
  - kernel/power/user.c:snapshot_write
  - kernel/power/user.c:snapshot_read
  - kernel/power/user.c:snapshot_release
  - kernel/power/user.c:snapshot_open
  - drivers/acpi/x86/s2idle.c:acpi_register_lps0_dev
```
**Symbols:**

```
ffffffff8117f350-ffffffff8117f387: lock_system_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
unsigned int lock_system_sleep();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81191720)
Location: kernel/power/main.c:52
Inline: True
Inline callers:
  - kernel/power/main.c:pm_test_store
Direct callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:s2idle_set_ops
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernation_set_ops
  - kernel/power/hibernate.c:hibernation_set_ops
  - kernel/power/user.c:snapshot_write
  - kernel/power/user.c:snapshot_read
  - kernel/power/user.c:snapshot_release
  - kernel/power/user.c:snapshot_open
  - drivers/acpi/x86/s2idle.c:acpi_register_lps0_dev
```
**Symbols:**

```
ffffffff81190060-ffffffff81190097: lock_system_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int lock_system_sleep();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff811a00e0)
Location: kernel/power/main.c:52
Inline: True
Inline callers:
  - kernel/power/main.c:pm_test_store
Direct callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:s2idle_set_ops
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernation_set_ops
  - kernel/power/hibernate.c:hibernation_set_ops
  - kernel/power/user.c:snapshot_write
  - kernel/power/user.c:snapshot_read
  - kernel/power/user.c:snapshot_release
  - kernel/power/user.c:snapshot_open
  - drivers/acpi/x86/s2idle.c:acpi_register_lps0_dev
```
**Symbols:**

```
ffffffff8119ea20-ffffffff8119ea57: lock_system_sleep (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void lock_system_sleep();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffff80001016f03c)
Location: kernel/power/main.c:24
Inline: True
Inline callers:
  - kernel/power/main.c:pm_test_store
Direct callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:s2idle_set_ops
```
**Symbols:**

```
ffff80001016e2a0-ffff80001016e2d4: lock_system_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void lock_system_sleep();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (c03b9bd4)
Location: kernel/power/main.c:24
Inline: True
Inline callers:
  - kernel/power/main.c:pm_test_store
Direct callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:s2idle_set_ops
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_write
  - kernel/power/user.c:snapshot_read
  - kernel/power/user.c:snapshot_release
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
c03b9108-c03b9148: lock_system_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void lock_system_sleep();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (c0000000001c6c78)
Location: kernel/power/main.c:24
Inline: True
Inline callers:
  - kernel/power/main.c:pm_test_store
Direct callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:s2idle_set_ops
```
**Symbols:**

```
c0000000001c5b90-c0000000001c5bdc: lock_system_sleep (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void lock_system_sleep();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81101033)
Location: kernel/power/main.c:24
Inline: True
Inline callers:
  - kernel/power/main.c:pm_test_store
Direct callers:
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_write
  - kernel/power/user.c:snapshot_read
  - kernel/power/user.c:snapshot_release
  - kernel/power/user.c:snapshot_open
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff81100660-ffffffff81100687: lock_system_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void lock_system_sleep();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810f12a3)
Location: kernel/power/main.c:24
Inline: True
Inline callers:
  - kernel/power/main.c:pm_test_store
Direct callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:s2idle_set_ops
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_write
  - kernel/power/user.c:snapshot_read
  - kernel/power/user.c:snapshot_release
  - kernel/power/user.c:snapshot_open
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff810f0850-ffffffff810f0877: lock_system_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void lock_system_sleep();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810fe273)
Location: kernel/power/main.c:24
Inline: True
Inline callers:
  - kernel/power/main.c:pm_test_store
Direct callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:s2idle_set_ops
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_write
  - kernel/power/user.c:snapshot_read
  - kernel/power/user.c:snapshot_release
  - kernel/power/user.c:snapshot_open
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff810fd820-ffffffff810fd847: lock_system_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void lock_system_sleep();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81109533)
Location: kernel/power/main.c:24
Inline: True
Inline callers:
  - kernel/power/main.c:pm_test_store
Direct callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:s2idle_set_ops
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_write
  - kernel/power/user.c:snapshot_read
  - kernel/power/user.c:snapshot_release
  - kernel/power/user.c:snapshot_open
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff81108ae0-ffffffff81108b07: lock_system_sleep (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>unsigned int</code>
</li>
</ul>
</details>
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
