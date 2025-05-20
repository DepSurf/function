# Function: <code>xen_cpuid_base</code>

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
In arch/x86/xen/enlighten.c (ffffffff81f606c2)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff814ce8ca)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff814ff8c1)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
```
In arch/x86/pci/xen.c (ffffffff81fb9046)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_msi_init
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
In arch/x86/xen/enlighten.c (ffffffff81f88329)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8151f4a2)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff815504e9)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
```
In arch/x86/pci/xen.c (ffffffff81fe6c1d)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_msi_init
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
In arch/x86/xen/enlighten.c (ffffffff81fc3717)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8154b95b)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8157cd69)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
```
In arch/x86/pci/xen.c (ffffffff82025461)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_msi_init
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
In arch/x86/xen/enlighten_hvm.c (ffffffff820a3b4c)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff820a58f3)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff820a75eb)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8155fc5f)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81590fd7)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
```
In arch/x86/pci/xen.c (ffffffff8210894e)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_msi_init
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
In arch/x86/xen/enlighten_hvm.c (ffffffff826aa24b)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff826abfba)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff826add9b)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh
```
```
In drivers/xen/grant-table.c (ffffffff815ba70a)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_request_version
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff815c3eff)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff815f4f51)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
```
```
In arch/x86/pci/xen.c (ffffffff827122a6)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_msi_init
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
In arch/x86/xen/enlighten_hvm.c (ffffffff826d33aa)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_platform_hvm
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff826d7139)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh
```
```
In drivers/xen/grant-table.c (0)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
```
```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8162ec0d)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
```
In arch/x86/pci/xen.c (0)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_msi_init
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
In arch/x86/xen/enlighten_hvm.c (ffffffff828892ce)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_platform_hvm
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff8288d1d1)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff8288e84a)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In drivers/xen/grant-table.c (0)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
```
```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8164c222)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
```
```
In arch/x86/pci/xen.c (0)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_msi_init
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
In arch/x86/xen/enlighten_hvm.c (ffffffff828a0568)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_platform_hvm
  - arch/x86/xen/enlighten_hvm.c:xen_parse_nopv
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff828a4666)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff828a5df1)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In drivers/xen/grant-table.c (0)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
```
```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81681013)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
```
```
In arch/x86/pci/xen.c (0)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_msi_init
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
In arch/x86/xen/enlighten_hvm.c (ffffffff828a3658)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_platform_hvm
  - arch/x86/xen/enlighten_hvm.c:xen_parse_nopv
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff828a76f6)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff828a8df9)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In drivers/xen/grant-table.c (0)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
```
```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816a36c3)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
```
```
In arch/x86/pci/xen.c (0)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_msi_init
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
In arch/x86/xen/enlighten_hvm.c (ffffffff82cc9968)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_platform_hvm
  - arch/x86/xen/enlighten_hvm.c:xen_parse_nopv
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff82ccbabf)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff82ccdad4)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff82cce764)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In drivers/xen/grant-table.c (0)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_need_v2
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8171c151)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xen_strict_xenbus_quirk
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81755c28)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
```
```
In arch/x86/pci/xen.c (ffffffff82d31aa4)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_msi_init
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
In arch/x86/xen/enlighten_hvm.c (ffffffff82fb57cd)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_platform_hvm
  - arch/x86/xen/enlighten_hvm.c:xen_parse_nopv
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff82fb792d)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff82fb9904)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff82fba5c0)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In drivers/xen/grant-table.c (0)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_need_v2
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81739101)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xen_strict_xenbus_quirk
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81770e98)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
```
```
In arch/x86/pci/xen.c (ffffffff83020ae4)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_hvm_msi_init
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
In arch/x86/xen/enlighten_hvm.c (ffffffff831bffd8)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_platform_hvm
  - arch/x86/xen/enlighten_hvm.c:xen_parse_nopv
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff831c1ec3)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff831c3fc4)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff831c4b45)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In drivers/xen/grant-table.c (0)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_request_version
```
```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81754958)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
```
```
In arch/x86/pci/xen.c (ffffffff8322bcb2)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_hvm_msi_init
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
In arch/x86/xen/enlighten_hvm.c (ffffffff832a0736)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_platform_hvm
  - arch/x86/xen/enlighten_hvm.c:xen_parse_nopv
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff832a2911)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff832a4b24)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff832a579e)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In drivers/xen/grant-table.c (0)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_request_version
```
```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff817d8018)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
```
```
In arch/x86/pci/xen.c (ffffffff833164d7)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_hvm_msi_init
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
In arch/x86/xen/enlighten_hvm.c (ffffffff8344f6e1)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_platform_hvm
  - arch/x86/xen/enlighten_hvm.c:msi_ext_dest_id
  - arch/x86/xen/enlighten_hvm.c:xen_parse_nopv
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff83451c9c)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff83453ce3)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff834547e0)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In drivers/xen/grant-table.c (ffffffff818c8a6a)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff818d691c)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81916285)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
```
```
In arch/x86/pci/xen.c (ffffffff834d0e4f)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_hvm_msi_init
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
In arch/x86/xen/enlighten_hvm.c (ffffffff83e6b8f1)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_platform_hvm
  - arch/x86/xen/enlighten_hvm.c:msi_ext_dest_id
  - arch/x86/xen/enlighten_hvm.c:xen_parse_nopv
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff83e6e94c)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff83e71472)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff83e72291)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In drivers/xen/grant-table.c (ffffffff81a19838)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_request_version
```
```
In drivers/xen/events/events_base.c (ffffffff83eea886)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_setup_upcall_vector
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81a28e72)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81a719a5)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
```
```
In arch/x86/pci/xen.c (ffffffff83f14fc3)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_hvm_msi_init
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
In arch/x86/xen/time.c (ffffffff8368b6c6)
Location: arch/x86/include/asm/xen/hypervisor.h:43
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff8368c391)
Location: arch/x86/include/asm/xen/hypervisor.h:43
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_platform_hvm
  - arch/x86/xen/enlighten_hvm.c:msi_ext_dest_id
  - arch/x86/xen/enlighten_hvm.c:xen_parse_nopv
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8368f2cc)
Location: arch/x86/include/asm/xen/hypervisor.h:43
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff836922c1)
Location: arch/x86/include/asm/xen/hypervisor.h:43
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff836931a1)
Location: arch/x86/include/asm/xen/hypervisor.h:43
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In drivers/xen/grant-table.c (ffffffff81a628b8)
Location: arch/x86/include/asm/xen/hypervisor.h:43
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_request_version
```
```
In drivers/xen/events/events_base.c (ffffffff83710276)
Location: arch/x86/include/asm/xen/hypervisor.h:43
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_setup_upcall_vector
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81a72572)
Location: arch/x86/include/asm/xen/hypervisor.h:43
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81abc255)
Location: arch/x86/include/asm/xen/hypervisor.h:43
Inline: True
```
```
In arch/x86/pci/xen.c (ffffffff8373b743)
Location: arch/x86/include/asm/xen/hypervisor.h:43
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_hvm_msi_init
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
In arch/x86/xen/time.c (ffffffff838bb286)
Location: arch/x86/include/asm/xen/hypervisor.h:44
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff838bbf51)
Location: arch/x86/include/asm/xen/hypervisor.h:44
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_platform_hvm
  - arch/x86/xen/enlighten_hvm.c:msi_ext_dest_id
  - arch/x86/xen/enlighten_hvm.c:xen_parse_nopv
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff838bf12c)
Location: arch/x86/include/asm/xen/hypervisor.h:44
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff838c1dd1)
Location: arch/x86/include/asm/xen/hypervisor.h:44
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff838c2d11)
Location: arch/x86/include/asm/xen/hypervisor.h:44
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In drivers/xen/grant-table.c (ffffffff81ab5818)
Location: arch/x86/include/asm/xen/hypervisor.h:44
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_request_version
```
```
In drivers/xen/events/events_base.c (ffffffff83943bf6)
Location: arch/x86/include/asm/xen/hypervisor.h:44
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_setup_upcall_vector
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81ac46d2)
Location: arch/x86/include/asm/xen/hypervisor.h:44
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81b0efa5)
Location: arch/x86/include/asm/xen/hypervisor.h:44
Inline: True
```
```
In arch/x86/pci/xen.c (ffffffff839700ce)
Location: arch/x86/include/asm/xen/hypervisor.h:44
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_hvm_msi_init
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff82891679)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_platform_hvm
  - arch/x86/xen/enlighten_hvm.c:xen_parse_nopv
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff82895706)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff82896e09)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In drivers/xen/grant-table.c (0)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
```
```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81669123)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
```
```
In arch/x86/pci/xen.c (0)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_msi_init
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
In arch/x86/platform/pvh/enlighten.c (ffffffff8288f142)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
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
In arch/x86/xen/enlighten_hvm.c (ffffffff828a4658)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_platform_hvm
  - arch/x86/xen/enlighten_hvm.c:xen_parse_nopv
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff828a86f6)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff828a9df9)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In drivers/xen/grant-table.c (0)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
```
```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81697503)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
```
```
In arch/x86/pci/xen.c (0)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_msi_init
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
In arch/x86/xen/enlighten_hvm.c (ffffffff828a462c)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_platform_hvm
  - arch/x86/xen/enlighten_hvm.c:xen_parse_nopv
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff828a8706)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff828a9e09)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In drivers/xen/grant-table.c (0)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
```
```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816b1bc3)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
```
```
In arch/x86/pci/xen.c (0)
Location: arch/x86/include/asm/xen/hypervisor.h:41
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_msi_init
```
</details>
</li>
</ul>

## Differences
