# Function: <code>suspend_disable_secondary_cpus</code>

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
In kernel/power/suspend.c (ffffffff810fcc4a)
Location: include/linux/cpu.h:143
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/power/hibernate.c (ffffffff810fe638)
Location: include/linux/cpu.h:143
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable
  - kernel/power/hibernate.c:hibernation_snapshot
```
```
In kernel/kexec_core.c (ffffffff8114eb75)
Location: include/linux/cpu.h:143
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
In kernel/power/suspend.c (ffffffff81109038)
Location: include/linux/cpu.h:148
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/power/hibernate.c (ffffffff8110aa88)
Location: include/linux/cpu.h:148
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable
  - kernel/power/hibernate.c:hibernation_snapshot
```
```
In kernel/kexec_core.c (ffffffff8115a885)
Location: include/linux/cpu.h:148
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
In kernel/power/suspend.c (ffffffff81113e42)
Location: include/linux/cpu.h:150
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/power/hibernate.c (ffffffff811156aa)
Location: include/linux/cpu.h:150
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable
  - kernel/power/hibernate.c:create_image
```
```
In kernel/kexec_core.c (ffffffff8116b657)
Location: include/linux/cpu.h:150
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
In kernel/power/suspend.c (ffffffff81110ade)
Location: include/linux/cpu.h:151
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/power/hibernate.c (ffffffff81111ffa)
Location: include/linux/cpu.h:151
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable
  - kernel/power/hibernate.c:create_image
```
```
In kernel/kexec_core.c (ffffffff81167d9d)
Location: include/linux/cpu.h:151
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
In kernel/power/suspend.c (ffffffff8111158e)
Location: include/linux/cpu.h:156
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/power/hibernate.c (ffffffff81112a1a)
Location: include/linux/cpu.h:156
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable
  - kernel/power/hibernate.c:create_image
```
```
In kernel/kexec_core.c (ffffffff81168b2d)
Location: include/linux/cpu.h:156
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
In kernel/power/suspend.c (ffffffff81130ff2)
Location: include/linux/cpu.h:150
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/power/hibernate.c (ffffffff81132a5a)
Location: include/linux/cpu.h:150
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable
  - kernel/power/hibernate.c:create_image
```
```
In kernel/kexec_core.c (ffffffff8118e88d)
Location: include/linux/cpu.h:150
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
In kernel/power/suspend.c (ffffffff81152933)
Location: include/linux/cpu.h:155
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/power/hibernate.c (ffffffff811549df)
Location: include/linux/cpu.h:155
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable
  - kernel/power/hibernate.c:create_image
```
```
In kernel/kexec_core.c (ffffffff811bdefe)
Location: include/linux/cpu.h:155
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
In kernel/power/suspend.c (ffffffff81181c3f)
Location: include/linux/cpu.h:155
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/power/hibernate.c (ffffffff811844e5)
Location: include/linux/cpu.h:155
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable
  - kernel/power/hibernate.c:create_image
```
```
In kernel/kexec_core.c (ffffffff811ffff8)
Location: include/linux/cpu.h:155
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
In kernel/power/suspend.c (ffffffff81192b1f)
Location: include/linux/cpu.h:159
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/power/hibernate.c (ffffffff81195275)
Location: include/linux/cpu.h:159
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable
  - kernel/power/hibernate.c:create_image
```
```
In kernel/kexec_core.c (ffffffff81215458)
Location: include/linux/cpu.h:159
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
In kernel/power/suspend.c (ffffffff811a150f)
Location: include/linux/cpu.h:171
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/power/hibernate.c (ffffffff811a3c55)
Location: include/linux/cpu.h:171
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable
  - kernel/power/hibernate.c:create_image
```
```
In kernel/kexec_core.c (ffffffff8122d3fd)
Location: include/linux/cpu.h:171
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
In kernel/power/suspend.c (ffff8000101709d4)
Location: include/linux/cpu.h:148
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
In kernel/power/suspend.c (c03bb33c)
Location: include/linux/cpu.h:148
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
```
```
In kernel/power/hibernate.c (c03bd248)
Location: include/linux/cpu.h:148
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable
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
In kernel/power/suspend.c (c0000000001c8aa0)
Location: include/linux/cpu.h:148
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
In kernel/power/hibernate.c (ffffffff81102ce8)
Location: include/linux/cpu.h:148
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable
  - kernel/power/hibernate.c:hibernation_snapshot
```
```
In kernel/kexec_core.c (ffffffff81152ea5)
Location: include/linux/cpu.h:148
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
In kernel/power/suspend.c (ffffffff810f261a)
Location: include/linux/cpu.h:148
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
```
```
In kernel/power/hibernate.c (ffffffff810f3f58)
Location: include/linux/cpu.h:148
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable
  - kernel/power/hibernate.c:hibernation_snapshot
```
```
In kernel/kexec_core.c (ffffffff811461c5)
Location: include/linux/cpu.h:148
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
In kernel/power/suspend.c (ffffffff810ff508)
Location: include/linux/cpu.h:148
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/power/hibernate.c (ffffffff81100f58)
Location: include/linux/cpu.h:148
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable
  - kernel/power/hibernate.c:hibernation_snapshot
```
```
In kernel/kexec_core.c (ffffffff81150d55)
Location: include/linux/cpu.h:148
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
In kernel/power/suspend.c (ffffffff8110a818)
Location: include/linux/cpu.h:148
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/power/hibernate.c (ffffffff8110c328)
Location: include/linux/cpu.h:148
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable
  - kernel/power/hibernate.c:hibernation_snapshot
```
```
In kernel/kexec_core.c (ffffffff8115db75)
Location: include/linux/cpu.h:148
Inline: True
Inline callers:
  - kernel/kexec_core.c:kernel_kexec
```
</details>
</li>
</ul>

## Differences
