# Function: <code>unlock_system_sleep</code>

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
In kernel/power/main.c (ffffffff810cd235)
Location: include/linux/suspend.h:443
Inline: True
Inline callers:
  - kernel/power/main.c:pm_test_store
```
```
In kernel/power/suspend.c (ffffffff810ce0ca)
Location: include/linux/suspend.h:443
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:freeze_set_ops
```
```
In kernel/power/hibernate.c (ffffffff810cf095)
Location: include/linux/suspend.h:443
Inline: True
Inline callers:
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:hibernate
```
```
In kernel/power/user.c (ffffffff810d5554)
Location: include/linux/suspend.h:443
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_release
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:snapshot_write
  - kernel/power/user.c:snapshot_read
```
```
In kernel/kexec_core.c (ffffffff8110db20)
Location: include/linux/suspend.h:443
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
In kernel/power/main.c (ffffffff810d1cd5)
Location: include/linux/suspend.h:442
Inline: True
Inline callers:
  - kernel/power/main.c:pm_test_store
```
```
In kernel/power/suspend.c (ffffffff810d2c2a)
Location: include/linux/suspend.h:442
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:freeze_set_ops
```
```
In kernel/power/hibernate.c (ffffffff810d47fa)
Location: include/linux/suspend.h:442
Inline: True
Inline callers:
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate
```
```
In kernel/power/user.c (ffffffff810da682)
Location: include/linux/suspend.h:442
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_write
  - kernel/power/user.c:snapshot_read
  - kernel/power/user.c:snapshot_release
  - kernel/power/user.c:snapshot_open
```
```
In kernel/kexec_core.c (ffffffff811155c0)
Location: include/linux/suspend.h:442
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
In kernel/power/main.c (ffffffff810d8875)
Location: include/linux/suspend.h:444
Inline: True
Inline callers:
  - kernel/power/main.c:pm_test_store
```
```
In kernel/power/suspend.c (ffffffff810d978b)
Location: include/linux/suspend.h:444
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:freeze_set_ops
```
```
In kernel/power/hibernate.c (ffffffff810db3aa)
Location: include/linux/suspend.h:444
Inline: True
Inline callers:
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate
```
```
In kernel/power/user.c (ffffffff810e1152)
Location: include/linux/suspend.h:444
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_write
  - kernel/power/user.c:snapshot_read
  - kernel/power/user.c:snapshot_release
  - kernel/power/user.c:snapshot_open
```
```
In kernel/kexec_core.c (ffffffff8111cce0)
Location: include/linux/suspend.h:444
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
In kernel/power/main.c (ffffffff810d7875)
Location: include/linux/suspend.h:447
Inline: True
Inline callers:
  - kernel/power/main.c:pm_test_store
```
```
In kernel/power/suspend.c (ffffffff810d876b)
Location: include/linux/suspend.h:447
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:freeze_set_ops
```
```
In kernel/power/hibernate.c (ffffffff810da49b)
Location: include/linux/suspend.h:447
Inline: True
Inline callers:
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernation_set_ops
```
```
In kernel/power/user.c (ffffffff810e0833)
Location: include/linux/suspend.h:447
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_write
  - kernel/power/user.c:snapshot_read
  - kernel/power/user.c:snapshot_release
  - kernel/power/user.c:snapshot_open
```
```
In kernel/kexec_core.c (ffffffff8111e90e)
Location: include/linux/suspend.h:447
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
In kernel/power/main.c (ffffffff810df8c5)
Location: include/linux/suspend.h:452
Inline: True
Inline callers:
  - kernel/power/main.c:pm_test_store
```
```
In kernel/power/suspend.c (ffffffff810e086b)
Location: include/linux/suspend.h:452
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:s2idle_set_ops
```
```
In kernel/power/hibernate.c (ffffffff810e262b)
Location: include/linux/suspend.h:452
Inline: True
Inline callers:
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernation_set_ops
```
```
In kernel/power/user.c (ffffffff810e8b03)
Location: include/linux/suspend.h:452
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_write
  - kernel/power/user.c:snapshot_read
  - kernel/power/user.c:snapshot_release
  - kernel/power/user.c:snapshot_open
```
```
In kernel/kexec_core.c (ffffffff8112a06e)
Location: include/linux/suspend.h:452
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
void unlock_system_sleep();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810e7ed2)
Location: kernel/power/main.c:32
Inline: True
Inline callers:
  - kernel/power/main.c:pm_test_store
Direct callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:s2idle_set_ops
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernation_set_ops
  - kernel/power/user.c:snapshot_write
  - kernel/power/user.c:snapshot_read
  - kernel/power/user.c:snapshot_release
  - kernel/power/user.c:snapshot_open
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff810e7780-ffffffff810e77a7: unlock_system_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void unlock_system_sleep();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810f34e2)
Location: kernel/power/main.c:31
Inline: True
Inline callers:
  - kernel/power/main.c:pm_test_store
Direct callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:s2idle_set_ops
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernation_set_ops
  - kernel/power/user.c:snapshot_write
  - kernel/power/user.c:snapshot_read
  - kernel/power/user.c:snapshot_release
  - kernel/power/user.c:snapshot_open
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff810f2d80-ffffffff810f2da7: unlock_system_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void unlock_system_sleep();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810fb9a2)
Location: kernel/power/main.c:30
Inline: True
Inline callers:
  - kernel/power/main.c:pm_test_store
Direct callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:s2idle_set_ops
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernation_set_ops
  - kernel/power/user.c:snapshot_write
  - kernel/power/user.c:snapshot_read
  - kernel/power/user.c:snapshot_release
  - kernel/power/user.c:snapshot_open
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff810fb250-ffffffff810fb277: unlock_system_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void unlock_system_sleep();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81107e12)
Location: kernel/power/main.c:31
Inline: True
Inline callers:
  - kernel/power/main.c:pm_test_store
Direct callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:s2idle_set_ops
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
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
ffffffff81107380-ffffffff811073a7: unlock_system_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void unlock_system_sleep();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81112e52)
Location: kernel/power/main.c:31
Inline: True
Inline callers:
  - kernel/power/main.c:pm_test_store
  - kernel/power/main.c:pm_test_store
Direct callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:s2idle_set_ops
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernation_set_ops
  - kernel/power/user.c:snapshot_write
  - kernel/power/user.c:snapshot_read
  - kernel/power/user.c:snapshot_release
  - kernel/power/user.c:snapshot_open
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff81111e80-ffffffff81111ea7: unlock_system_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void unlock_system_sleep();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff8110ff22)
Location: kernel/power/main.c:31
Inline: True
Inline callers:
  - kernel/power/main.c:pm_test_store
  - kernel/power/main.c:pm_test_store
Direct callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:s2idle_set_ops
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernation_set_ops
  - kernel/power/user.c:snapshot_write
  - kernel/power/user.c:snapshot_read
  - kernel/power/user.c:snapshot_release
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff8110ef50-ffffffff8110ef77: unlock_system_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void unlock_system_sleep();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81110962)
Location: kernel/power/main.c:31
Inline: True
Inline callers:
  - kernel/power/main.c:pm_test_store
  - kernel/power/main.c:pm_test_store
Direct callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:s2idle_set_ops
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernation_set_ops
  - kernel/power/user.c:snapshot_write
  - kernel/power/user.c:snapshot_read
  - kernel/power/user.c:snapshot_release
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff8110f9f0-ffffffff8110fa17: unlock_system_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void unlock_system_sleep();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81130412)
Location: kernel/power/main.c:31
Inline: True
Inline callers:
  - kernel/power/main.c:pm_test_store
  - kernel/power/main.c:pm_test_store
Direct callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:s2idle_set_ops
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernation_set_ops
  - kernel/power/user.c:snapshot_write
  - kernel/power/user.c:snapshot_read
  - kernel/power/user.c:snapshot_release
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff8112f340-ffffffff8112f367: unlock_system_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void unlock_system_sleep();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81151c2b)
Location: kernel/power/main.c:31
Inline: True
Inline callers:
  - kernel/power/main.c:pm_test_store
  - kernel/power/main.c:pm_test_store
Direct callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:s2idle_set_ops
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernation_set_ops
  - kernel/power/user.c:snapshot_write
  - kernel/power/user.c:snapshot_read
  - kernel/power/user.c:snapshot_release
  - kernel/power/user.c:snapshot_open
  - drivers/acpi/x86/s2idle.c:acpi_register_lps0_dev
```
**Symbols:**

```
ffffffff81150990-ffffffff811509bf: unlock_system_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void unlock_system_sleep(unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff8118095e)
Location: kernel/power/main.c:33
Inline: True
Inline callers:
  - kernel/power/main.c:pm_test_store
Direct callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:s2idle_set_ops
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernation_set_ops
  - kernel/power/user.c:snapshot_write
  - kernel/power/user.c:snapshot_read
  - kernel/power/user.c:snapshot_release
  - kernel/power/user.c:snapshot_open
  - drivers/acpi/x86/s2idle.c:acpi_register_lps0_dev
```
**Symbols:**

```
ffffffff8117f3a0-ffffffff8117f3d7: unlock_system_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void unlock_system_sleep(unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff8119177e)
Location: kernel/power/main.c:61
Inline: True
Inline callers:
  - kernel/power/main.c:pm_test_store
Direct callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:s2idle_set_ops
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernation_set_ops
  - kernel/power/user.c:snapshot_write
  - kernel/power/user.c:snapshot_read
  - kernel/power/user.c:snapshot_release
  - kernel/power/user.c:snapshot_open
  - drivers/acpi/x86/s2idle.c:acpi_register_lps0_dev
```
**Symbols:**

```
ffffffff811900b0-ffffffff811900e7: unlock_system_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void unlock_system_sleep(unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff811a013e)
Location: kernel/power/main.c:61
Inline: True
Inline callers:
  - kernel/power/main.c:pm_test_store
Direct callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:s2idle_set_ops
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/hibernate.c:hibernation_set_ops
  - kernel/power/user.c:snapshot_write
  - kernel/power/user.c:snapshot_read
  - kernel/power/user.c:snapshot_release
  - kernel/power/user.c:snapshot_open
  - drivers/acpi/x86/s2idle.c:acpi_register_lps0_dev
```
**Symbols:**

```
ffffffff8119ea70-ffffffff8119eaa7: unlock_system_sleep (STB_GLOBAL)
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
void unlock_system_sleep();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffff80001016f0c0)
Location: kernel/power/main.c:31
Inline: True
Inline callers:
  - kernel/power/main.c:pm_test_store
Direct callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:s2idle_set_ops
```
**Symbols:**

```
ffff80001016e2d8-ffff80001016e30c: unlock_system_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void unlock_system_sleep();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (c03b9c7c)
Location: kernel/power/main.c:31
Inline: True
Inline callers:
  - kernel/power/main.c:pm_test_store
Direct callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:s2idle_set_ops
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_write
  - kernel/power/user.c:snapshot_read
  - kernel/power/user.c:snapshot_release
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
c03b9148-c03b9188: unlock_system_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void unlock_system_sleep();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (c0000000001c6d20)
Location: kernel/power/main.c:31
Inline: True
Inline callers:
  - kernel/power/main.c:pm_test_store
Direct callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:s2idle_set_ops
```
**Symbols:**

```
c0000000001c5be0-c0000000001c5c2c: unlock_system_sleep (STB_GLOBAL)
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
void unlock_system_sleep();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff811010a2)
Location: kernel/power/main.c:31
Inline: True
Inline callers:
  - kernel/power/main.c:pm_test_store
Direct callers:
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
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
ffffffff81100690-ffffffff811006b7: unlock_system_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void unlock_system_sleep();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810f1312)
Location: kernel/power/main.c:31
Inline: True
Inline callers:
  - kernel/power/main.c:pm_test_store
Direct callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:s2idle_set_ops
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
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
ffffffff810f0880-ffffffff810f08a7: unlock_system_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void unlock_system_sleep();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810fe2e2)
Location: kernel/power/main.c:31
Inline: True
Inline callers:
  - kernel/power/main.c:pm_test_store
Direct callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:s2idle_set_ops
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
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
ffffffff810fd850-ffffffff810fd877: unlock_system_sleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void unlock_system_sleep();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff811095a2)
Location: kernel/power/main.c:31
Inline: True
Inline callers:
  - kernel/power/main.c:pm_test_store
Direct callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:s2idle_set_ops
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
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
ffffffff81108b10-ffffffff81108b37: unlock_system_sleep (STB_GLOBAL)
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
<b>Param added. </b>
<code>unsigned int flags</code>
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
