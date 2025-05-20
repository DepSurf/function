# Function: <code>this_cpu_hvclock</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff81073740)
Location: arch/x86/kernel/kvmclock.c:62
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_register_clock
  - arch/x86/kernel/kvmclock.c:kvm_check_and_clear_guest_paused
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
In arch/x86/kernel/kvmclock.c (ffffffff810772c0)
Location: arch/x86/kernel/kvmclock.c:62
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_register_clock
  - arch/x86/kernel/kvmclock.c:kvm_check_and_clear_guest_paused
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
In arch/x86/kernel/kvmclock.c (ffffffff81078350)
Location: arch/x86/kernel/kvmclock.c:62
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_register_clock
  - arch/x86/kernel/kvmclock.c:kvm_check_and_clear_guest_paused
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
In arch/x86/kernel/kvmclock.c (ffffffff8107f880)
Location: arch/x86/kernel/kvmclock.c:62
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_setup_secondary_clock
  - arch/x86/kernel/kvmclock.c:kvm_restore_sched_clock_state
  - arch/x86/kernel/kvmclock.c:kvm_check_and_clear_guest_paused
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff8107f4e0)
Location: arch/x86/kernel/kvmclock.c:61
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_setup_secondary_clock
  - arch/x86/kernel/kvmclock.c:kvm_restore_sched_clock_state
  - arch/x86/kernel/kvmclock.c:kvm_check_and_clear_guest_paused
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff810805c0)
Location: arch/x86/kernel/kvmclock.c:60
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_setup_secondary_clock
  - arch/x86/kernel/kvmclock.c:kvm_restore_sched_clock_state
  - arch/x86/kernel/kvmclock.c:kvm_check_and_clear_guest_paused
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff8108f4f0)
Location: arch/x86/include/asm/kvmclock.h:16
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_setup_secondary_clock
  - arch/x86/kernel/kvmclock.c:kvm_restore_sched_clock_state
  - arch/x86/kernel/kvmclock.c:kvm_check_and_clear_guest_paused
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff810a00a0)
Location: arch/x86/include/asm/kvmclock.h:16
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_register_clock
  - arch/x86/kernel/kvmclock.c:kvm_check_and_clear_guest_paused
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff810b7af0)
Location: arch/x86/include/asm/kvmclock.h:16
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_register_clock
  - arch/x86/kernel/kvmclock.c:kvm_check_and_clear_guest_paused
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff810bace0)
Location: arch/x86/include/asm/kvmclock.h:16
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_register_clock
  - arch/x86/kernel/kvmclock.c:kvm_check_and_clear_guest_paused
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff810c2120)
Location: arch/x86/include/asm/kvmclock.h:16
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_register_clock
  - arch/x86/kernel/kvmclock.c:kvm_check_and_clear_guest_paused
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvmclock.c (ffffffff81077350)
Location: arch/x86/kernel/kvmclock.c:62
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_register_clock
  - arch/x86/kernel/kvmclock.c:kvm_check_and_clear_guest_paused
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
In arch/x86/kernel/kvmclock.c (ffffffff81067450)
Location: arch/x86/kernel/kvmclock.c:62
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_register_clock
  - arch/x86/kernel/kvmclock.c:kvm_check_and_clear_guest_paused
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
In arch/x86/kernel/kvmclock.c (ffffffff81077300)
Location: arch/x86/kernel/kvmclock.c:62
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_register_clock
  - arch/x86/kernel/kvmclock.c:kvm_check_and_clear_guest_paused
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
In arch/x86/kernel/kvmclock.c (ffffffff81079390)
Location: arch/x86/kernel/kvmclock.c:62
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_register_clock
  - arch/x86/kernel/kvmclock.c:kvm_check_and_clear_guest_paused
```
</details>
</li>
</ul>

## Differences
