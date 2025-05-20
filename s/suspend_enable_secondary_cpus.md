# Function: <code>suspend_enable_secondary_cpus</code>

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
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (ffffffff810fccb3)
Location: include/linux/cpu.h:152
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/power/hibernate.c (ffffffff810fe646)
Location: include/linux/cpu.h:152
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
```
```
In kernel/kexec_core.c (ffffffff8114eb83)
Location: include/linux/cpu.h:152
Inline: True
Inline callers:
  - kernel/kexec_core.c:kernel_kexec
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
In kernel/power/suspend.c (ffffffff811090a1)
Location: include/linux/cpu.h:157
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/power/hibernate.c (ffffffff8110aa96)
Location: include/linux/cpu.h:157
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
```
```
In kernel/kexec_core.c (ffffffff8115a893)
Location: include/linux/cpu.h:157
Inline: True
Inline callers:
  - kernel/kexec_core.c:kernel_kexec
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
In kernel/power/suspend.c (ffffffff81113eab)
Location: include/linux/cpu.h:159
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/power/hibernate.c (ffffffff811156b8)
Location: include/linux/cpu.h:159
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:resume_target_kernel
  - kernel/power/hibernate.c:create_image
```
```
In kernel/kexec_core.c (ffffffff8116b665)
Location: include/linux/cpu.h:159
Inline: True
Inline callers:
  - kernel/kexec_core.c:kernel_kexec
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
In kernel/power/suspend.c (ffffffff81110b47)
Location: include/linux/cpu.h:160
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/power/hibernate.c (ffffffff81112008)
Location: include/linux/cpu.h:160
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:resume_target_kernel
  - kernel/power/hibernate.c:create_image
```
```
In kernel/kexec_core.c (ffffffff81167dab)
Location: include/linux/cpu.h:160
Inline: True
Inline callers:
  - kernel/kexec_core.c:kernel_kexec
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
In kernel/power/suspend.c (ffffffff811115f7)
Location: include/linux/cpu.h:165
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/power/hibernate.c (ffffffff81112a28)
Location: include/linux/cpu.h:165
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_restore
  - kernel/power/hibernate.c:create_image
```
```
In kernel/kexec_core.c (ffffffff81168b3b)
Location: include/linux/cpu.h:165
Inline: True
Inline callers:
  - kernel/kexec_core.c:kernel_kexec
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
In kernel/power/suspend.c (ffffffff8113105b)
Location: include/linux/cpu.h:159
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/power/hibernate.c (ffffffff81132a68)
Location: include/linux/cpu.h:159
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_restore
  - kernel/power/hibernate.c:create_image
```
```
In kernel/kexec_core.c (ffffffff8118e89b)
Location: include/linux/cpu.h:159
Inline: True
Inline callers:
  - kernel/kexec_core.c:kernel_kexec
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
In kernel/power/suspend.c (ffffffff81152998)
Location: include/linux/cpu.h:164
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/power/hibernate.c (ffffffff811549ec)
Location: include/linux/cpu.h:164
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:resume_target_kernel
  - kernel/power/hibernate.c:create_image
```
```
In kernel/kexec_core.c (ffffffff811bdf0b)
Location: include/linux/cpu.h:164
Inline: True
Inline callers:
  - kernel/kexec_core.c:kernel_kexec
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
In kernel/power/suspend.c (ffffffff81181ca4)
Location: include/linux/cpu.h:164
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/power/hibernate.c (ffffffff811844f2)
Location: include/linux/cpu.h:164
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:resume_target_kernel
  - kernel/power/hibernate.c:create_image
```
```
In kernel/kexec_core.c (ffffffff811fffcb)
Location: include/linux/cpu.h:164
Inline: True
Inline callers:
  - kernel/kexec_core.c:kernel_kexec
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
In kernel/power/suspend.c (ffffffff81192b84)
Location: include/linux/cpu.h:168
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/power/hibernate.c (ffffffff81195282)
Location: include/linux/cpu.h:168
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:resume_target_kernel
  - kernel/power/hibernate.c:create_image
```
```
In kernel/kexec_core.c (ffffffff8121542b)
Location: include/linux/cpu.h:168
Inline: True
Inline callers:
  - kernel/kexec_core.c:kernel_kexec
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
In kernel/power/suspend.c (ffffffff811a1574)
Location: include/linux/cpu.h:180
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/power/hibernate.c (ffffffff811a3c62)
Location: include/linux/cpu.h:180
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:resume_target_kernel
  - kernel/power/hibernate.c:create_image
```
```
In kernel/kexec_core.c (ffffffff8122d3d0)
Location: include/linux/cpu.h:180
Inline: True
Inline callers:
  - kernel/kexec_core.c:kernel_kexec
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
In kernel/power/suspend.c (ffff800010170a30)
Location: include/linux/cpu.h:157
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (c03bb3a0)
Location: include/linux/cpu.h:157
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
```
```
In kernel/power/hibernate.c (c03bd254)
Location: include/linux/cpu.h:157
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
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
In kernel/power/suspend.c (c0000000001c8b2c)
Location: include/linux/cpu.h:157
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
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
In kernel/power/hibernate.c (ffffffff81102cf6)
Location: include/linux/cpu.h:157
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
```
```
In kernel/kexec_core.c (ffffffff81152eb3)
Location: include/linux/cpu.h:157
Inline: True
Inline callers:
  - kernel/kexec_core.c:kernel_kexec
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
In kernel/power/suspend.c (ffffffff810f2680)
Location: include/linux/cpu.h:157
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
```
```
In kernel/power/hibernate.c (ffffffff810f3f66)
Location: include/linux/cpu.h:157
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
```
```
In kernel/kexec_core.c (ffffffff811461d3)
Location: include/linux/cpu.h:157
Inline: True
Inline callers:
  - kernel/kexec_core.c:kernel_kexec
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
In kernel/power/suspend.c (ffffffff810ff571)
Location: include/linux/cpu.h:157
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/power/hibernate.c (ffffffff81100f66)
Location: include/linux/cpu.h:157
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
```
```
In kernel/kexec_core.c (ffffffff81150d63)
Location: include/linux/cpu.h:157
Inline: True
Inline callers:
  - kernel/kexec_core.c:kernel_kexec
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
In kernel/power/suspend.c (ffffffff8110a881)
Location: include/linux/cpu.h:157
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/power/hibernate.c (ffffffff8110c336)
Location: include/linux/cpu.h:157
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
```
```
In kernel/kexec_core.c (ffffffff8115db83)
Location: include/linux/cpu.h:157
Inline: True
Inline callers:
  - kernel/kexec_core.c:kernel_kexec
```
</details>
</li>
</ul>

## Differences
