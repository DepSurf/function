# Function: <code>get_num_wrps</code>

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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/hw_breakpoint.c (ffff800011435f50)
Location: arch/arm64/include/asm/hw_breakpoint.h:149
Inline: True
Inline callers:
  - arch/arm64/kernel/hw_breakpoint.c:arch_hw_breakpoint_init
  - arch/arm64/kernel/hw_breakpoint.c:hw_breakpoint_slots
```
```
In arch/arm64/kvm/debug.c (ffff8000100d4540)
Location: arch/arm64/include/asm/hw_breakpoint.h:149
Inline: True
Inline callers:
  - arch/arm64/kvm/debug.c:kvm_arm_clear_debug
  - arch/arm64/kvm/debug.c:kvm_arm_setup_debug
```
```
In arch/arm64/kvm/reset.c (ffff8000100d4850)
Location: arch/arm64/include/asm/hw_breakpoint.h:149
Inline: True
Inline callers:
  - arch/arm64/kvm/reset.c:kvm_arch_vm_ioctl_check_extension
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
In arch/arm/kernel/hw_breakpoint.c (c15066c0)
Location: arch/arm/kernel/hw_breakpoint.c:185
Inline: True
Inline callers:
  - arch/arm/kernel/hw_breakpoint.c:arch_hw_breakpoint_init
  - arch/arm/kernel/hw_breakpoint.c:arch_hw_breakpoint_init
  - arch/arm/kernel/hw_breakpoint.c:hw_breakpoint_slots
  - arch/arm/kernel/hw_breakpoint.c:hw_breakpoint_slots
```
</details>
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
