# Function: <code>HYPERVISOR_vm_assist</code>

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
In arch/x86/xen/setup.c (ffffffff81f620d9)
Location: arch/x86/include/asm/xen/hypercall.h:416
Inline: True
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
In arch/x86/xen/setup.c (ffffffff81f89d53)
Location: arch/x86/include/asm/xen/hypercall.h:417
Inline: True
```
```
In drivers/xen/time.c (ffffffff81fd0eab)
Location: arch/x86/include/asm/xen/hypercall.h:417
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_time_setup_guest
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
In arch/x86/xen/setup.c (ffffffff81fc514d)
Location: arch/x86/include/asm/xen/hypercall.h:417
Inline: True
```
```
In drivers/xen/time.c (ffffffff8200e823)
Location: arch/x86/include/asm/xen/hypercall.h:417
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_time_setup_guest
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
In arch/x86/xen/setup.c (ffffffff820a4f72)
Location: arch/x86/include/asm/xen/hypercall.h:422
Inline: True
```
```
In drivers/xen/time.c (ffffffff820f02ce)
Location: arch/x86/include/asm/xen/hypercall.h:422
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_time_setup_guest
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
In arch/x86/xen/setup.c (ffffffff826ab674)
Location: arch/x86/include/asm/xen/hypercall.h:422
Inline: True
```
```
In drivers/xen/time.c (ffffffff826f9acf)
Location: arch/x86/include/asm/xen/hypercall.h:422
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_time_setup_guest
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
In arch/x86/xen/setup.c (ffffffff826d47f8)
Location: arch/x86/include/asm/xen/hypercall.h:422
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_pvmmu_arch_setup
  - arch/x86/xen/setup.c:xen_pvmmu_arch_setup
  - arch/x86/xen/setup.c:xen_pvmmu_arch_setup
```
```
In drivers/xen/time.c (ffffffff82723e6b)
Location: arch/x86/include/asm/xen/hypercall.h:422
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_time_setup_guest
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
In arch/x86/xen/setup.c (ffffffff8288a7ad)
Location: arch/x86/include/asm/xen/hypercall.h:376
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_pvmmu_arch_setup
  - arch/x86/xen/setup.c:xen_pvmmu_arch_setup
  - arch/x86/xen/setup.c:xen_pvmmu_arch_setup
```
```
In drivers/xen/time.c (ffffffff828dc044)
Location: arch/x86/include/asm/xen/hypercall.h:376
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_time_setup_guest
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
In arch/x86/xen/setup.c (ffffffff828a1b6a)
Location: arch/x86/include/asm/xen/hypercall.h:386
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_pvmmu_arch_setup
  - arch/x86/xen/setup.c:xen_pvmmu_arch_setup
  - arch/x86/xen/setup.c:xen_pvmmu_arch_setup
```
```
In drivers/xen/time.c (ffffffff828f693d)
Location: arch/x86/include/asm/xen/hypercall.h:386
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_time_setup_guest
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
In arch/x86/xen/setup.c (ffffffff828a4c2a)
Location: arch/x86/include/asm/xen/hypercall.h:386
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_pvmmu_arch_setup
  - arch/x86/xen/setup.c:xen_pvmmu_arch_setup
  - arch/x86/xen/setup.c:xen_pvmmu_arch_setup
```
```
In drivers/xen/time.c (ffffffff828ff994)
Location: arch/x86/include/asm/xen/hypercall.h:386
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_time_setup_guest
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
In arch/x86/xen/setup.c (ffffffff82ccaf8d)
Location: arch/x86/include/asm/xen/hypercall.h:386
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_pvmmu_arch_setup
  - arch/x86/xen/setup.c:xen_pvmmu_arch_setup
  - arch/x86/xen/setup.c:xen_pvmmu_arch_setup
```
```
In drivers/xen/time.c (ffffffff82d16d17)
Location: arch/x86/include/asm/xen/hypercall.h:386
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_time_setup_guest
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
In arch/x86/xen/setup.c (ffffffff82fb6dfb)
Location: arch/x86/include/asm/xen/hypercall.h:386
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_pvmmu_arch_setup
  - arch/x86/xen/setup.c:xen_pvmmu_arch_setup
  - arch/x86/xen/setup.c:xen_pvmmu_arch_setup
```
```
In drivers/xen/time.c (ffffffff830048d0)
Location: arch/x86/include/asm/xen/hypercall.h:386
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_time_setup_guest
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
In arch/x86/xen/setup.c (ffffffff831c15c4)
Location: arch/x86/include/asm/xen/hypercall.h:386
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_arch_setup
  - arch/x86/xen/setup.c:xen_arch_setup
  - arch/x86/xen/setup.c:xen_arch_setup
```
```
In drivers/xen/time.c (ffffffff8320f379)
Location: arch/x86/include/asm/xen/hypercall.h:386
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_time_setup_guest
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
In arch/x86/xen/setup.c (ffffffff832a2071)
Location: arch/x86/include/asm/xen/hypercall.h:386
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_arch_setup
  - arch/x86/xen/setup.c:xen_arch_setup
  - arch/x86/xen/setup.c:xen_arch_setup
```
```
In drivers/xen/time.c (ffffffff832f830a)
Location: arch/x86/include/asm/xen/hypercall.h:386
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_time_setup_guest
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
In arch/x86/xen/setup.c (ffffffff834510fd)
Location: arch/x86/include/asm/xen/hypercall.h:456
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_arch_setup
  - arch/x86/xen/setup.c:xen_arch_setup
  - arch/x86/xen/setup.c:xen_arch_setup
```
```
In drivers/xen/time.c (ffffffff834b0b30)
Location: arch/x86/include/asm/xen/hypercall.h:456
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_time_setup_guest
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
In arch/x86/xen/setup.c (ffffffff83e6d9e1)
Location: arch/x86/include/asm/xen/hypercall.h:456
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_arch_setup
  - arch/x86/xen/setup.c:xen_arch_setup
  - arch/x86/xen/setup.c:xen_arch_setup
```
```
In drivers/xen/time.c (ffffffff83eea785)
Location: arch/x86/include/asm/xen/hypercall.h:456
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_time_setup_guest
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
In arch/x86/xen/setup.c (ffffffff8368e591)
Location: arch/x86/include/asm/xen/hypercall.h:456
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_arch_setup
```
```
In drivers/xen/time.c (ffffffff83710175)
Location: arch/x86/include/asm/xen/hypercall.h:456
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_time_setup_guest
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
In arch/x86/xen/setup.c (ffffffff838be181)
Location: arch/x86/include/asm/xen/hypercall.h:456
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_arch_setup
```
```
In drivers/xen/time.c (ffffffff83943af5)
Location: arch/x86/include/asm/xen/hypercall.h:456
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_time_setup_guest
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
  - drivers/xen/time.c:xen_time_setup_guest
```
**Symbols:**

```
ffff8000100f0d80-ffff8000100f0d8c: HYPERVISOR_vm_assist (STB_GLOBAL)
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
In arch/x86/xen/setup.c (ffffffff82892c42)
Location: arch/x86/include/asm/xen/hypercall.h:386
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_pvmmu_arch_setup
  - arch/x86/xen/setup.c:xen_pvmmu_arch_setup
  - arch/x86/xen/setup.c:xen_pvmmu_arch_setup
```
```
In drivers/xen/time.c (ffffffff828e71b1)
Location: arch/x86/include/asm/xen/hypercall.h:386
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_time_setup_guest
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
In arch/x86/xen/setup.c (ffffffff828a5c2a)
Location: arch/x86/include/asm/xen/hypercall.h:386
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_pvmmu_arch_setup
  - arch/x86/xen/setup.c:xen_pvmmu_arch_setup
  - arch/x86/xen/setup.c:xen_pvmmu_arch_setup
```
```
In drivers/xen/time.c (ffffffff828facb7)
Location: arch/x86/include/asm/xen/hypercall.h:386
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_time_setup_guest
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
In arch/x86/xen/setup.c (ffffffff828a5bfe)
Location: arch/x86/include/asm/xen/hypercall.h:386
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_pvmmu_arch_setup
  - arch/x86/xen/setup.c:xen_pvmmu_arch_setup
  - arch/x86/xen/setup.c:xen_pvmmu_arch_setup
```
```
In drivers/xen/time.c (ffffffff829009e8)
Location: arch/x86/include/asm/xen/hypercall.h:386
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_time_setup_guest
```
</details>
</li>
</ul>

## Differences
