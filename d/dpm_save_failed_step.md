# Function: <code>dpm_save_failed_step</code>

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
In kernel/power/suspend.c (ffffffff810cec68)
Location: include/linux/suspend.h:92
Inline: True
Inline callers:
  - kernel/power/suspend.c:pm_suspend
```
```
In drivers/base/power/main.c (ffffffff81559f73)
Location: include/linux/suspend.h:92
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_start
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
In kernel/power/suspend.c (ffffffff810d3776)
Location: include/linux/suspend.h:91
Inline: True
Inline callers:
  - kernel/power/suspend.c:pm_suspend
```
```
In drivers/base/power/main.c (ffffffff815ad805)
Location: include/linux/suspend.h:91
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend_start
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
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
In kernel/power/suspend.c (ffffffff810da306)
Location: include/linux/suspend.h:91
Inline: True
Inline callers:
  - kernel/power/suspend.c:pm_suspend
```
```
In drivers/base/power/main.c (ffffffff815dc5c5)
Location: include/linux/suspend.h:91
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend_start
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
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
In kernel/power/suspend.c (ffffffff810d93f6)
Location: include/linux/suspend.h:91
Inline: True
Inline callers:
  - kernel/power/suspend.c:pm_suspend
```
```
In drivers/base/power/main.c (ffffffff815f1135)
Location: include/linux/suspend.h:91
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend_start
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
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
In kernel/power/suspend.c (ffffffff810e1571)
Location: include/linux/suspend.h:92
Inline: True
```
```
In drivers/base/power/main.c (ffffffff816586b5)
Location: include/linux/suspend.h:92
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend_start
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (ffffffff810e9b50)
Location: include/linux/suspend.h:92
Inline: True
```
```
In drivers/base/power/main.c (ffffffff81694074)
Location: include/linux/suspend.h:92
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend_start
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (ffffffff810f5170)
Location: include/linux/suspend.h:92
Inline: True
```
```
In drivers/base/power/main.c (ffffffff816b46f4)
Location: include/linux/suspend.h:92
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend_start
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (ffffffff810fd67b)
Location: include/linux/suspend.h:92
Inline: True
```
```
In drivers/base/power/main.c (ffffffff816ee5a7)
Location: include/linux/suspend.h:92
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend_start
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
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
In kernel/power/suspend.c (ffffffff81109ac7)
Location: include/linux/suspend.h:92
Inline: True
```
```
In drivers/base/power/main.c (ffffffff81712587)
Location: include/linux/suspend.h:92
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend_start
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
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
In kernel/power/suspend.c (ffffffff811144c9)
Location: include/linux/suspend.h:92
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_prepare
```
```
In drivers/base/power/main.c (ffffffff817cddb7)
Location: include/linux/suspend.h:92
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend_start
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
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
In kernel/power/suspend.c (ffffffff81bded75)
Location: include/linux/suspend.h:92
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_prepare
```
```
In drivers/base/power/main.c (ffffffff817e26c7)
Location: include/linux/suspend.h:92
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend_start
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
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
In kernel/power/suspend.c (ffffffff81bd10e9)
Location: include/linux/suspend.h:92
Inline: True
Inline callers:
  - kernel/power/suspend.c:enter_state
```
```
In drivers/base/power/main.c (ffffffff817c6aa7)
Location: include/linux/suspend.h:92
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend_start
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
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
In kernel/power/suspend.c (ffffffff811315da)
Location: include/linux/suspend.h:92
Inline: True
Inline callers:
  - kernel/power/suspend.c:enter_state
```
```
In drivers/base/power/main.c (ffffffff81850e6a)
Location: include/linux/suspend.h:92
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend_start
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
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
In kernel/power/suspend.c (ffffffff8115305a)
Location: include/linux/suspend.h:92
Inline: True
Inline callers:
  - kernel/power/suspend.c:enter_state
```
```
In drivers/base/power/main.c (ffffffff8199693a)
Location: include/linux/suspend.h:92
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend_start
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
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
In kernel/power/suspend.c (ffffffff811823fb)
Location: include/linux/suspend.h:92
Inline: True
Inline callers:
  - kernel/power/suspend.c:enter_state
```
```
In drivers/base/power/main.c (ffffffff81b0769a)
Location: include/linux/suspend.h:92
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend_start
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
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
In kernel/power/suspend.c (ffffffff811932cf)
Location: include/linux/suspend.h:95
Inline: True
Inline callers:
  - kernel/power/suspend.c:enter_state
```
```
In drivers/base/power/main.c (ffffffff81b556ea)
Location: include/linux/suspend.h:95
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend_start
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
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
In kernel/power/suspend.c (ffffffff811a1cbf)
Location: include/linux/suspend.h:95
Inline: True
Inline callers:
  - kernel/power/suspend.c:enter_state
```
```
In drivers/base/power/main.c (ffffffff81badcaa)
Location: include/linux/suspend.h:95
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend_start
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_noirq
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (ffff800010171290)
Location: include/linux/suspend.h:92
Inline: True
```
```
In drivers/base/power/main.c (ffff800010903134)
Location: include/linux/suspend.h:92
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend_start
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
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
In kernel/power/suspend.c (c03bbdb8)
Location: include/linux/suspend.h:92
Inline: True
```
```
In drivers/base/power/main.c (c09ed534)
Location: include/linux/suspend.h:92
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend_start
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (c0000000001c97c4)
Location: include/linux/suspend.h:92
Inline: True
```
```
In drivers/base/power/main.c (c0000000009a1804)
Location: include/linux/suspend.h:92
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend_start
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816d8907)
Location: include/linux/suspend.h:92
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend_start
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
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
In kernel/power/suspend.c (ffffffff810f2fb4)
Location: include/linux/suspend.h:92
Inline: True
```
```
In drivers/base/power/main.c (ffffffff816b2f57)
Location: include/linux/suspend.h:92
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend_start
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
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
In kernel/power/suspend.c (ffffffff810fff97)
Location: include/linux/suspend.h:92
Inline: True
```
```
In drivers/base/power/main.c (ffffffff81706247)
Location: include/linux/suspend.h:92
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend_start
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
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
In kernel/power/suspend.c (ffffffff8110b337)
Location: include/linux/suspend.h:92
Inline: True
```
```
In drivers/base/power/main.c (ffffffff81720c67)
Location: include/linux/suspend.h:92
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend_start
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
```
</details>
</li>
</ul>

## Differences
