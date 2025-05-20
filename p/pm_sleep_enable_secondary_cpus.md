# Function: <code>pm_sleep_enable_secondary_cpus</code>

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
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (ffffffff81152998)
Location: kernel/power/power.h:323
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/power/hibernate.c (ffffffff811549ec)
Location: kernel/power/power.h:323
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:resume_target_kernel
  - kernel/power/hibernate.c:create_image
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
Location: kernel/power/power.h:323
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/power/hibernate.c (ffffffff811844f2)
Location: kernel/power/power.h:323
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:resume_target_kernel
  - kernel/power/hibernate.c:create_image
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
Location: kernel/power/power.h:323
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/power/hibernate.c (ffffffff81195282)
Location: kernel/power/power.h:323
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:resume_target_kernel
  - kernel/power/hibernate.c:create_image
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
Location: kernel/power/power.h:325
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/power/hibernate.c (ffffffff811a3c62)
Location: kernel/power/power.h:325
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:resume_target_kernel
  - kernel/power/hibernate.c:create_image
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
