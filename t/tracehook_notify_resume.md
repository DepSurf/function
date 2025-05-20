# Function: <code>tracehook_notify_resume</code>

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
In arch/x86/entry/common.c (ffffffff8100318d)
Location: include/linux/tracehook.h:182
Inline: True
Inline callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff8100321d)
Location: include/linux/tracehook.h:182
Inline: True
Inline callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81003291)
Location: include/linux/tracehook.h:182
Inline: True
Inline callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff8100312b)
Location: include/linux/tracehook.h:182
Inline: True
Inline callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff810035f5)
Location: include/linux/tracehook.h:182
Inline: True
Inline callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81003fa0)
Location: include/linux/tracehook.h:183
Inline: True
Inline callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81003d00)
Location: include/linux/tracehook.h:179
Inline: True
Inline callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff8100412b)
Location: include/linux/tracehook.h:179
Inline: True
Inline callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff8100412b)
Location: include/linux/tracehook.h:179
Inline: True
Inline callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff810050b9)
Location: include/linux/tracehook.h:179
Inline: True
Inline callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
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
In kernel/entry/common.c (ffffffff8113ba6a)
Location: include/linux/tracehook.h:180
Inline: True
Inline callers:
  - kernel/entry/common.c:exit_to_user_mode_loop
```
```
In kernel/entry/kvm.c (ffffffff8113bea3)
Location: include/linux/tracehook.h:180
Inline: True
Inline callers:
  - kernel/entry/kvm.c:xfer_to_guest_mode_work
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
In kernel/entry/common.c (ffffffff8113cd3a)
Location: include/linux/tracehook.h:180
Inline: True
Inline callers:
  - kernel/entry/common.c:exit_to_user_mode_loop
```
```
In kernel/entry/kvm.c (ffffffff8113d15b)
Location: include/linux/tracehook.h:180
Inline: True
Inline callers:
  - kernel/entry/kvm.c:xfer_to_guest_mode_handle_work
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
In kernel/entry/common.c (ffffffff8115fe5a)
Location: include/linux/tracehook.h:180
Inline: True
Inline callers:
  - kernel/entry/common.c:exit_to_user_mode_loop
```
```
In kernel/entry/kvm.c (ffffffff811602aa)
Location: include/linux/tracehook.h:180
Inline: True
Inline callers:
  - kernel/entry/kvm.c:xfer_to_guest_mode_work
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/signal.c (ffff800010093364)
Location: include/linux/tracehook.h:179
Inline: True
Inline callers:
  - arch/arm64/kernel/signal.c:do_notify_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/signal.c (c030e794)
Location: include/linux/tracehook.h:179
Inline: True
Inline callers:
  - arch/arm/kernel/signal.c:do_work_pending
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
In arch/powerpc/kernel/signal.c (c000000000023958)
Location: include/linux/tracehook.h:179
Inline: True
Inline callers:
  - arch/powerpc/kernel/signal.c:do_notify_resume
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
In arch/riscv/kernel/signal.c (ffffffe0000b6a4e)
Location: include/linux/tracehook.h:179
Inline: True
Inline callers:
  - arch/riscv/kernel/signal.c:do_notify_resume
```
</details>
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
In arch/x86/entry/common.c (ffffffff8100412b)
Location: include/linux/tracehook.h:179
Inline: True
Inline callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff810023f0)
Location: include/linux/tracehook.h:179
Inline: True
Inline callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81004123)
Location: include/linux/tracehook.h:179
Inline: True
Inline callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff8100420b)
Location: include/linux/tracehook.h:179
Inline: True
Inline callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
```
</details>
</li>
</ul>

## Differences
