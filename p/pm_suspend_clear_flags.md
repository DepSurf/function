# Function: <code>pm_suspend_clear_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (ffffffff810ceb77)
Location: include/linux/suspend.h:210
Inline: True
Inline callers:
  - kernel/power/suspend.c:pm_suspend
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
In kernel/power/suspend.c (ffffffff810d369f)
Location: include/linux/suspend.h:209
Inline: True
Inline callers:
  - kernel/power/suspend.c:pm_suspend
```
```
In kernel/power/hibernate.c (ffffffff810d3f15)
Location: include/linux/suspend.h:209
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_snapshot
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
In kernel/power/suspend.c (ffffffff810da22f)
Location: include/linux/suspend.h:209
Inline: True
Inline callers:
  - kernel/power/suspend.c:pm_suspend
```
```
In kernel/power/hibernate.c (ffffffff810daaa5)
Location: include/linux/suspend.h:209
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_snapshot
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
In kernel/power/suspend.c (ffffffff810d931a)
Location: include/linux/suspend.h:211
Inline: True
Inline callers:
  - kernel/power/suspend.c:pm_suspend
```
```
In kernel/power/hibernate.c (ffffffff810d9b75)
Location: include/linux/suspend.h:211
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_snapshot
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
In kernel/power/suspend.c (ffffffff810e1446)
Location: include/linux/suspend.h:215
Inline: True
```
```
In kernel/power/hibernate.c (ffffffff810e1d17)
Location: include/linux/suspend.h:215
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_snapshot
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
In kernel/power/suspend.c (ffffffff810e9aab)
Location: include/linux/suspend.h:215
Inline: True
```
```
In kernel/power/hibernate.c (ffffffff810ea1d5)
Location: include/linux/suspend.h:215
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_snapshot
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
In kernel/power/suspend.c (ffffffff810f50cb)
Location: include/linux/suspend.h:215
Inline: True
```
```
In kernel/power/hibernate.c (ffffffff810f5805)
Location: include/linux/suspend.h:215
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_snapshot
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
In kernel/power/suspend.c (ffffffff810fd5d2)
Location: include/linux/suspend.h:216
Inline: True
```
```
In kernel/power/hibernate.c (ffffffff810fdd15)
Location: include/linux/suspend.h:216
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_snapshot
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
In kernel/power/suspend.c (ffffffff81109a1e)
Location: include/linux/suspend.h:217
Inline: True
```
```
In kernel/power/hibernate.c (ffffffff8110a145)
Location: include/linux/suspend.h:217
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_snapshot
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
In kernel/power/suspend.c (ffffffff811146ca)
Location: include/linux/suspend.h:217
Inline: True
Inline callers:
  - kernel/power/suspend.c:enter_state
```
```
In kernel/power/hibernate.c (ffffffff81114fd5)
Location: include/linux/suspend.h:217
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_snapshot
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
In kernel/power/suspend.c (ffffffff81bdef5b)
Location: include/linux/suspend.h:217
Inline: True
Inline callers:
  - kernel/power/suspend.c:enter_state
```
```
In kernel/power/hibernate.c (ffffffff8111158d)
Location: include/linux/suspend.h:217
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernation_snapshot
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
In kernel/power/suspend.c (ffffffff81bd0ffd)
Location: include/linux/suspend.h:217
Inline: True
Inline callers:
  - kernel/power/suspend.c:enter_state
```
```
In kernel/power/hibernate.c (ffffffff81111fdd)
Location: include/linux/suspend.h:217
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernation_snapshot
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
In kernel/power/suspend.c (ffffffff81131551)
Location: include/linux/suspend.h:217
Inline: True
Inline callers:
  - kernel/power/suspend.c:enter_state
```
```
In kernel/power/hibernate.c (ffffffff81131ffd)
Location: include/linux/suspend.h:217
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernation_snapshot
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
In kernel/power/suspend.c (ffffffff81152f70)
Location: include/linux/suspend.h:217
Inline: True
Inline callers:
  - kernel/power/suspend.c:enter_state
```
```
In kernel/power/hibernate.c (ffffffff81153d12)
Location: include/linux/suspend.h:217
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernation_snapshot
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
In kernel/power/suspend.c (ffffffff8118235f)
Location: include/linux/suspend.h:218
Inline: True
Inline callers:
  - kernel/power/suspend.c:enter_state
```
```
In kernel/power/hibernate.c (ffffffff8118327c)
Location: include/linux/suspend.h:218
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernation_snapshot
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
In kernel/power/suspend.c (ffffffff81193233)
Location: include/linux/suspend.h:222
Inline: True
Inline callers:
  - kernel/power/suspend.c:enter_state
```
```
In kernel/power/hibernate.c (ffffffff811940ec)
Location: include/linux/suspend.h:222
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernation_snapshot
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
In kernel/power/suspend.c (ffffffff811a1c23)
Location: include/linux/suspend.h:222
Inline: True
Inline callers:
  - kernel/power/suspend.c:enter_state
```
```
In kernel/power/hibernate.c (ffffffff811a2adc)
Location: include/linux/suspend.h:222
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernation_snapshot
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
In kernel/power/suspend.c (ffff8000101711c8)
Location: include/linux/suspend.h:217
Inline: True
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
In kernel/power/suspend.c (c03bbcec)
Location: include/linux/suspend.h:217
Inline: True
```
```
In kernel/power/hibernate.c (c03bc70c)
Location: include/linux/suspend.h:217
Inline: True
Inline callers:
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
In kernel/power/suspend.c (c0000000001c96e8)
Location: include/linux/suspend.h:217
Inline: True
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
In kernel/power/hibernate.c (0)
Location: include/linux/suspend.h:335
Inline: True
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
In kernel/power/suspend.c (ffffffff810f2f0b)
Location: include/linux/suspend.h:217
Inline: True
```
```
In kernel/power/hibernate.c (ffffffff810f3635)
Location: include/linux/suspend.h:217
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_snapshot
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
In kernel/power/suspend.c (ffffffff810ffeee)
Location: include/linux/suspend.h:217
Inline: True
```
```
In kernel/power/hibernate.c (ffffffff81100615)
Location: include/linux/suspend.h:217
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_snapshot
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
In kernel/power/suspend.c (ffffffff8110b28e)
Location: include/linux/suspend.h:217
Inline: True
```
```
In kernel/power/hibernate.c (ffffffff8110b9b5)
Location: include/linux/suspend.h:217
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_snapshot
```
</details>
</li>
</ul>

## Differences
