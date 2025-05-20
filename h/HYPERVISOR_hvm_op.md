# Function: <code>HYPERVISOR_hvm_op</code>

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
In arch/x86/xen/mmu.c (ffffffff8101e03e)
Location: arch/x86/include/asm/xen/hypercall.h:456
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_oldmem_pfn_is_ram
  - arch/x86/xen/mmu.c:xen_hvm_init_mmu_ops
```
```
In drivers/xen/events/events_base.c (ffffffff814c7710)
Location: arch/x86/include/asm/xen/hypercall.h:456
Inline: True
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff814cedbb)
Location: arch/x86/include/asm/xen/hypercall.h:456
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff814ff539)
Location: arch/x86/include/asm/xen/hypercall.h:456
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
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
In arch/x86/xen/mmu.c (ffffffff81f8b33b)
Location: arch/x86/include/asm/xen/hypercall.h:457
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_hvm_init_mmu_ops
  - arch/x86/xen/mmu.c:xen_oldmem_pfn_is_ram
```
```
In drivers/xen/events/events_base.c (ffffffff81518180)
Location: arch/x86/include/asm/xen/hypercall.h:457
Inline: True
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8151f9bb)
Location: arch/x86/include/asm/xen/hypercall.h:457
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81550404)
Location: arch/x86/include/asm/xen/hypercall.h:457
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
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
In arch/x86/xen/mmu.c (ffffffff81fc6729)
Location: arch/x86/include/asm/xen/hypercall.h:457
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_hvm_init_mmu_ops
  - arch/x86/xen/mmu.c:xen_oldmem_pfn_is_ram
```
```
In drivers/xen/events/events_base.c (ffffffff81544690)
Location: arch/x86/include/asm/xen/hypercall.h:457
Inline: True
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8154be6b)
Location: arch/x86/include/asm/xen/hypercall.h:457
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8157cc84)
Location: arch/x86/include/asm/xen/hypercall.h:457
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
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
In arch/x86/xen/mmu_hvm.c (ffffffff820a3db9)
Location: arch/x86/include/asm/xen/hypercall.h:462
Inline: True
Inline callers:
  - arch/x86/xen/mmu_hvm.c:xen_hvm_init_mmu_ops
  - arch/x86/xen/mmu_hvm.c:xen_oldmem_pfn_is_ram
```
```
In drivers/xen/events/events_base.c (ffffffff81558520)
Location: arch/x86/include/asm/xen/hypercall.h:462
Inline: True
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8156004b)
Location: arch/x86/include/asm/xen/hypercall.h:462
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81590ee9)
Location: arch/x86/include/asm/xen/hypercall.h:462
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
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
In arch/x86/xen/mmu_hvm.c (ffffffff826aa49b)
Location: arch/x86/include/asm/xen/hypercall.h:462
Inline: True
Inline callers:
  - arch/x86/xen/mmu_hvm.c:xen_hvm_init_mmu_ops
  - arch/x86/xen/mmu_hvm.c:xen_oldmem_pfn_is_ram
```
```
In drivers/xen/events/events_base.c (ffffffff815bc8d0)
Location: arch/x86/include/asm/xen/hypercall.h:462
Inline: True
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff815c42eb)
Location: arch/x86/include/asm/xen/hypercall.h:462
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff815f5a39)
Location: arch/x86/include/asm/xen/hypercall.h:462
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
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
In arch/x86/xen/mmu_hvm.c (ffffffff826d362b)
Location: arch/x86/include/asm/xen/hypercall.h:462
Inline: True
Inline callers:
  - arch/x86/xen/mmu_hvm.c:xen_hvm_init_mmu_ops
  - arch/x86/xen/mmu_hvm.c:xen_oldmem_pfn_is_ram
```
```
In drivers/xen/events/events_base.c (ffffffff815f4f86)
Location: arch/x86/include/asm/xen/hypercall.h:462
Inline: True
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff815fc9e3)
Location: arch/x86/include/asm/xen/hypercall.h:462
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8162eb64)
Location: arch/x86/include/asm/xen/hypercall.h:462
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
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
In arch/x86/xen/mmu_hvm.c (ffffffff8288954f)
Location: arch/x86/include/asm/xen/hypercall.h:410
Inline: True
Inline callers:
  - arch/x86/xen/mmu_hvm.c:xen_hvm_init_mmu_ops
  - arch/x86/xen/mmu_hvm.c:xen_oldmem_pfn_is_ram
```
```
In drivers/xen/events/events_base.c (ffffffff81610076)
Location: arch/x86/include/asm/xen/hypercall.h:410
Inline: True
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81617b03)
Location: arch/x86/include/asm/xen/hypercall.h:410
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8164cda4)
Location: arch/x86/include/asm/xen/hypercall.h:410
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
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
In arch/x86/xen/mmu_hvm.c (ffffffff828a08de)
Location: arch/x86/include/asm/xen/hypercall.h:420
Inline: True
Inline callers:
  - arch/x86/xen/mmu_hvm.c:xen_hvm_init_mmu_ops
  - arch/x86/xen/mmu_hvm.c:xen_oldmem_pfn_is_ram
```
```
In drivers/xen/events/events_base.c (ffffffff81643e46)
Location: arch/x86/include/asm/xen/hypercall.h:420
Inline: True
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8164b7b3)
Location: arch/x86/include/asm/xen/hypercall.h:420
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816818ba)
Location: arch/x86/include/asm/xen/hypercall.h:420
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
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
In arch/x86/xen/mmu_hvm.c (ffffffff828a39c2)
Location: arch/x86/include/asm/xen/hypercall.h:420
Inline: True
Inline callers:
  - arch/x86/xen/mmu_hvm.c:xen_hvm_init_mmu_ops
  - arch/x86/xen/mmu_hvm.c:xen_oldmem_pfn_is_ram
```
```
In drivers/xen/events/events_base.c (ffffffff816663f6)
Location: arch/x86/include/asm/xen/hypercall.h:420
Inline: True
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8166dc43)
Location: arch/x86/include/asm/xen/hypercall.h:420
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816a3f6a)
Location: arch/x86/include/asm/xen/hypercall.h:420
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
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
In arch/x86/xen/mmu_hvm.c (ffffffff82cc9cc8)
Location: arch/x86/include/asm/xen/hypercall.h:420
Inline: True
Inline callers:
  - arch/x86/xen/mmu_hvm.c:xen_hvm_init_mmu_ops
  - arch/x86/xen/mmu_hvm.c:xen_oldmem_pfn_is_ram
```
```
In drivers/xen/events/events_base.c (ffffffff81715b46)
Location: arch/x86/include/asm/xen/hypercall.h:420
Inline: True
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8171e303)
Location: arch/x86/include/asm/xen/hypercall.h:420
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81756767)
Location: arch/x86/include/asm/xen/hypercall.h:420
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
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
In arch/x86/xen/mmu_hvm.c (ffffffff82fb5b36)
Location: arch/x86/include/asm/xen/hypercall.h:420
Inline: True
Inline callers:
  - arch/x86/xen/mmu_hvm.c:xen_hvm_init_mmu_ops
  - arch/x86/xen/mmu_hvm.c:xen_oldmem_pfn_is_ram
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8173b283)
Location: arch/x86/include/asm/xen/hypercall.h:420
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff817719d7)
Location: arch/x86/include/asm/xen/hypercall.h:420
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
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
In arch/x86/xen/mmu_hvm.c (ffffffff831c0341)
Location: arch/x86/include/asm/xen/hypercall.h:420
Inline: True
Inline callers:
  - arch/x86/xen/mmu_hvm.c:xen_hvm_init_mmu_ops
  - arch/x86/xen/mmu_hvm.c:xen_oldmem_pfn_is_ram
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8171edc4)
Location: arch/x86/include/asm/xen/hypercall.h:420
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8175547d)
Location: arch/x86/include/asm/xen/hypercall.h:420
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
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
In arch/x86/xen/mmu_hvm.c (ffffffff832a0b2b)
Location: arch/x86/include/asm/xen/hypercall.h:420
Inline: True
Inline callers:
  - arch/x86/xen/mmu_hvm.c:xen_hvm_init_mmu_ops
  - arch/x86/xen/mmu_hvm.c:xen_hvm_exit_mmap
  - arch/x86/xen/mmu_hvm.c:xen_oldmem_pfn_is_ram
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8179db7a)
Location: arch/x86/include/asm/xen/hypercall.h:420
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff817d8bad)
Location: arch/x86/include/asm/xen/hypercall.h:420
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
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
In arch/x86/xen/mmu_hvm.c (ffffffff8344fafb)
Location: arch/x86/include/asm/xen/hypercall.h:482
Inline: True
Inline callers:
  - arch/x86/xen/mmu_hvm.c:xen_hvm_init_mmu_ops
  - arch/x86/xen/mmu_hvm.c:xen_hvm_exit_mmap
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff818d7e85)
Location: arch/x86/include/asm/xen/hypercall.h:482
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_late_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81916f25)
Location: arch/x86/include/asm/xen/hypercall.h:482
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
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
In arch/x86/xen/mmu_hvm.c (ffffffff83e6baee)
Location: arch/x86/include/asm/xen/hypercall.h:482
Inline: True
Inline callers:
  - arch/x86/xen/mmu_hvm.c:xen_hvm_init_mmu_ops
  - arch/x86/xen/mmu_hvm.c:xen_hvm_exit_mmap
```
```
In drivers/xen/events/events_base.c (ffffffff83eea971)
Location: arch/x86/include/asm/xen/hypercall.h:482
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_setup_upcall_vector
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff83eeb0c8)
Location: arch/x86/include/asm/xen/hypercall.h:482
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_late_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81a7230b)
Location: arch/x86/include/asm/xen/hypercall.h:482
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
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
In arch/x86/xen/mmu_hvm.c (ffffffff8368c58e)
Location: arch/x86/include/asm/xen/hypercall.h:482
Inline: True
Inline callers:
  - arch/x86/xen/mmu_hvm.c:xen_hvm_init_mmu_ops
  - arch/x86/xen/mmu_hvm.c:xen_hvm_exit_mmap
```
```
In drivers/xen/events/events_base.c (ffffffff83710361)
Location: arch/x86/include/asm/xen/hypercall.h:482
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_setup_upcall_vector
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff83710ad8)
Location: arch/x86/include/asm/xen/hypercall.h:482
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_late_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81abcbcb)
Location: arch/x86/include/asm/xen/hypercall.h:482
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
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
In arch/x86/xen/mmu_hvm.c (ffffffff838bc14e)
Location: arch/x86/include/asm/xen/hypercall.h:482
Inline: True
Inline callers:
  - arch/x86/xen/mmu_hvm.c:xen_hvm_init_mmu_ops
  - arch/x86/xen/mmu_hvm.c:xen_hvm_exit_mmap
```
```
In drivers/xen/events/events_base.c (ffffffff83943ce1)
Location: arch/x86/include/asm/xen/hypercall.h:482
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_setup_upcall_vector
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff83944458)
Location: arch/x86/include/asm/xen/hypercall.h:482
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_late_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81b0f9bb)
Location: arch/x86/include/asm/xen/hypercall.h:482
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/arm/xen/enlighten.c:xen_guest_init
  - drivers/xen/events/events_base.c:xen_set_callback_via
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
```
**Symbols:**

```
ffff8000100f0d2c-ffff8000100f0d38: HYPERVISOR_hvm_op (STB_GLOBAL)
```
</details>
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_hvm.c (ffffffff828919e8)
Location: arch/x86/include/asm/xen/hypercall.h:420
Inline: True
Inline callers:
  - arch/x86/xen/mmu_hvm.c:xen_hvm_init_mmu_ops
  - arch/x86/xen/mmu_hvm.c:xen_oldmem_pfn_is_ram
```
```
In drivers/xen/events/events_base.c (ffffffff8162c126)
Location: arch/x86/include/asm/xen/hypercall.h:420
Inline: True
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81633a53)
Location: arch/x86/include/asm/xen/hypercall.h:420
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816699ca)
Location: arch/x86/include/asm/xen/hypercall.h:420
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_hvm.c (ffffffff828a49c2)
Location: arch/x86/include/asm/xen/hypercall.h:420
Inline: True
Inline callers:
  - arch/x86/xen/mmu_hvm.c:xen_hvm_init_mmu_ops
  - arch/x86/xen/mmu_hvm.c:xen_oldmem_pfn_is_ram
```
```
In drivers/xen/events/events_base.c (ffffffff8165a236)
Location: arch/x86/include/asm/xen/hypercall.h:420
Inline: True
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81661a83)
Location: arch/x86/include/asm/xen/hypercall.h:420
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81697daa)
Location: arch/x86/include/asm/xen/hypercall.h:420
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
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
In arch/x86/xen/mmu_hvm.c (ffffffff828a4996)
Location: arch/x86/include/asm/xen/hypercall.h:420
Inline: True
Inline callers:
  - arch/x86/xen/mmu_hvm.c:xen_hvm_init_mmu_ops
  - arch/x86/xen/mmu_hvm.c:xen_oldmem_pfn_is_ram
```
```
In drivers/xen/events/events_base.c (ffffffff81674806)
Location: arch/x86/include/asm/xen/hypercall.h:420
Inline: True
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8167c053)
Location: arch/x86/include/asm/xen/hypercall.h:420
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816b232a)
Location: arch/x86/include/asm/xen/hypercall.h:420
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
```
</details>
</li>
</ul>

## Differences
