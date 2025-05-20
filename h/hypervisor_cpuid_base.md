# Function: <code>hypervisor_cpuid_base</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8107c973)
Location: arch/x86/include/asm/processor.h:816
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81063d27)
Location: arch/x86/include/asm/processor.h:816
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff814ce8ca)
Location: arch/x86/include/asm/processor.h:816
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff814ff8c1)
Location: arch/x86/include/asm/processor.h:816
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
```
In arch/x86/pci/xen.c (ffffffff81fb9046)
Location: arch/x86/include/asm/processor.h:816
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_msi_init
```
**Symbols:**

```
ffffffff8107c973-ffffffff8107c9fb: hypervisor_cpuid_base.constprop.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8107e3d6)
Location: arch/x86/include/asm/processor.h:829
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81063933)
Location: arch/x86/include/asm/processor.h:829
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8151f4a2)
Location: arch/x86/include/asm/processor.h:829
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff815504e9)
Location: arch/x86/include/asm/processor.h:829
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
```
In arch/x86/pci/xen.c (ffffffff81fe6c1d)
Location: arch/x86/include/asm/processor.h:829
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_msi_init
```
**Symbols:**

```
ffffffff8107e3d6-ffffffff8107e46b: hypervisor_cpuid_base.constprop.24 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff810829e9)
Location: arch/x86/include/asm/processor.h:898
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81066de3)
Location: arch/x86/include/asm/processor.h:898
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8154b95b)
Location: arch/x86/include/asm/processor.h:898
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8157cd69)
Location: arch/x86/include/asm/processor.h:898
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
```
In arch/x86/pci/xen.c (ffffffff82025461)
Location: arch/x86/include/asm/processor.h:898
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_msi_init
```
**Symbols:**

```
ffffffff810829e9-ffffffff81082a7e: hypervisor_cpuid_base.constprop.24 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff8101ba0a)
Location: arch/x86/include/asm/processor.h:918
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff820a58f3)
Location: arch/x86/include/asm/processor.h:918
Inline: True
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff820a75eb)
Location: arch/x86/include/asm/processor.h:918
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh
```
```
In arch/x86/kernel/kvm.c (ffffffff810660b5)
Location: arch/x86/include/asm/processor.h:918
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8155fc5f)
Location: arch/x86/include/asm/processor.h:918
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81590fd7)
Location: arch/x86/include/asm/processor.h:918
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
```
In arch/x86/pci/xen.c (ffffffff8210894e)
Location: arch/x86/include/asm/processor.h:918
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_msi_init
```
**Symbols:**

```
ffffffff8101ba0a-ffffffff8101bac2: hypervisor_cpuid_base.constprop.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff8101c6fa)
Location: arch/x86/include/asm/processor.h:945
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff826abfba)
Location: arch/x86/include/asm/processor.h:945
Inline: True
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff826add9b)
Location: arch/x86/include/asm/processor.h:945
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh
```
```
In arch/x86/kernel/kvm.c (ffffffff8106a145)
Location: arch/x86/include/asm/processor.h:945
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In drivers/xen/grant-table.c (ffffffff815ba70a)
Location: arch/x86/include/asm/processor.h:945
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_request_version
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff815c3eff)
Location: arch/x86/include/asm/processor.h:945
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff815f4f51)
Location: arch/x86/include/asm/processor.h:945
Inline: True
```
```
In arch/x86/pci/xen.c (ffffffff827122a6)
Location: arch/x86/include/asm/processor.h:945
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_msi_init
```
**Symbols:**

```
ffffffff8101c6fa-ffffffff8101c7b2: hypervisor_cpuid_base.constprop.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff8101d11a)
Location: arch/x86/include/asm/processor.h:959
Inline: True
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_platform_hvm
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: arch/x86/include/asm/processor.h:959
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff826d7139)
Location: arch/x86/include/asm/processor.h:959
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh
```
```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/include/asm/processor.h:959
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In arch/x86/kernel/jailhouse.c (0)
Location: arch/x86/include/asm/processor.h:959
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: arch/x86/include/asm/processor.h:959
Inline: True
```
```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: arch/x86/include/asm/processor.h:959
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8162ec0d)
Location: arch/x86/include/asm/processor.h:959
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_raw_console_write
```
```
In arch/x86/pci/xen.c (0)
Location: arch/x86/include/asm/processor.h:959
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_msi_init
```
**Symbols:**

```
ffffffff8101d11a-ffffffff8101d1d2: hypervisor_cpuid_base.constprop.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff8101c7fa)
Location: arch/x86/include/asm/processor.h:954
Inline: True
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_platform_hvm
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: arch/x86/include/asm/processor.h:954
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff8288d1d1)
Location: arch/x86/include/asm/processor.h:954
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff8288e84a)
Location: arch/x86/include/asm/processor.h:954
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/include/asm/processor.h:954
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In arch/x86/kernel/jailhouse.c (0)
Location: arch/x86/include/asm/processor.h:954
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: arch/x86/include/asm/processor.h:954
Inline: True
```
```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: arch/x86/include/asm/processor.h:954
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8164c222)
Location: arch/x86/include/asm/processor.h:954
Inline: True
```
```
In arch/x86/pci/xen.c (0)
Location: arch/x86/include/asm/processor.h:954
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_msi_init
```
**Symbols:**

```
ffffffff8101c7fa-ffffffff8101c8b2: hypervisor_cpuid_base.constprop.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff8101e32a)
Location: arch/x86/include/asm/processor.h:944
Inline: True
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_platform_hvm
  - arch/x86/xen/enlighten_hvm.c:xen_parse_nopv
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: arch/x86/include/asm/processor.h:944
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff828a4666)
Location: arch/x86/include/asm/processor.h:944
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff828a5df1)
Location: arch/x86/include/asm/processor.h:944
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff828b086f)
Location: arch/x86/include/asm/processor.h:944
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_detect
```
```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/include/asm/processor.h:944
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In arch/x86/kernel/jailhouse.c (ffffffff810783c0)
Location: arch/x86/include/asm/processor.h:944
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_paravirt
Direct callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_detect
```
```
In drivers/xen/grant-table.c (0)
Location: arch/x86/include/asm/processor.h:944
Inline: True
```
```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: arch/x86/include/asm/processor.h:944
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81681013)
Location: arch/x86/include/asm/processor.h:944
Inline: True
```
```
In arch/x86/pci/xen.c (0)
Location: arch/x86/include/asm/processor.h:944
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_msi_init
```
**Symbols:**

```
ffffffff8101e32a-ffffffff8101e3da: hypervisor_cpuid_base.constprop.0 (STB_LOCAL)
ffffffff810783c0-ffffffff81078468: hypervisor_cpuid_base.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff8101ecaa)
Location: arch/x86/include/asm/processor.h:944
Inline: True
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_platform_hvm
  - arch/x86/xen/enlighten_hvm.c:xen_parse_nopv
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: arch/x86/include/asm/processor.h:944
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff828a76f6)
Location: arch/x86/include/asm/processor.h:944
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff828a8df9)
Location: arch/x86/include/asm/processor.h:944
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff828b3cbc)
Location: arch/x86/include/asm/processor.h:944
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_detect
```
```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/include/asm/processor.h:944
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In arch/x86/kernel/jailhouse.c (ffffffff81079410)
Location: arch/x86/include/asm/processor.h:944
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_paravirt
Direct callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_detect
```
```
In drivers/xen/grant-table.c (0)
Location: arch/x86/include/asm/processor.h:944
Inline: True
```
```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: arch/x86/include/asm/processor.h:944
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816a36c3)
Location: arch/x86/include/asm/processor.h:944
Inline: True
```
```
In arch/x86/pci/xen.c (0)
Location: arch/x86/include/asm/processor.h:944
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_msi_init
```
**Symbols:**

```
ffffffff8101ecaa-ffffffff8101ed5a: hypervisor_cpuid_base.constprop.0 (STB_LOCAL)
ffffffff81079410-ffffffff810794b8: hypervisor_cpuid_base.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff81021277)
Location: arch/x86/include/asm/processor.h:946
Inline: True
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_platform_hvm
  - arch/x86/xen/enlighten_hvm.c:xen_parse_nopv
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff82ccbabf)
Location: arch/x86/include/asm/processor.h:946
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff82ccdad4)
Location: arch/x86/include/asm/processor.h:946
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff82cce764)
Location: arch/x86/include/asm/processor.h:946
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff82cd8d66)
Location: arch/x86/include/asm/processor.h:946
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_detect
```
```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/include/asm/processor.h:946
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In arch/x86/kernel/jailhouse.c (ffffffff810807ab)
Location: arch/x86/include/asm/processor.h:946
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: arch/x86/include/asm/processor.h:946
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_need_v2
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8171c151)
Location: arch/x86/include/asm/processor.h:946
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xen_strict_xenbus_quirk
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81755c28)
Location: arch/x86/include/asm/processor.h:946
Inline: True
```
```
In arch/x86/pci/xen.c (ffffffff82d31aa4)
Location: arch/x86/include/asm/processor.h:946
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_msi_init
```
**Symbols:**

```
ffffffff81021277-ffffffff8102130c: hypervisor_cpuid_base.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff81bd28be)
Location: arch/x86/include/asm/processor.h:812
Inline: True
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_platform_hvm
  - arch/x86/xen/enlighten_hvm.c:xen_parse_nopv
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff82fb792d)
Location: arch/x86/include/asm/processor.h:812
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff82fb9904)
Location: arch/x86/include/asm/processor.h:812
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff82fba5c0)
Location: arch/x86/include/asm/processor.h:812
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff82fc5184)
Location: arch/x86/include/asm/processor.h:812
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_detect
```
```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/include/asm/processor.h:812
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In arch/x86/kernel/jailhouse.c (ffffffff810803c1)
Location: arch/x86/include/asm/processor.h:812
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: arch/x86/include/asm/processor.h:812
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_need_v2
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81739101)
Location: arch/x86/include/asm/processor.h:812
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xen_strict_xenbus_quirk
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81770e98)
Location: arch/x86/include/asm/processor.h:812
Inline: True
```
```
In arch/x86/pci/xen.c (ffffffff83020ae4)
Location: arch/x86/include/asm/processor.h:812
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_hvm_msi_init
```
**Symbols:**

```
ffffffff81bd28be-ffffffff81bd2953: hypervisor_cpuid_base.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff81bc4a5c)
Location: arch/x86/include/asm/processor.h:796
Inline: True
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_platform_hvm
  - arch/x86/xen/enlighten_hvm.c:xen_parse_nopv
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff831c1ec3)
Location: arch/x86/include/asm/processor.h:796
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff831c3fc4)
Location: arch/x86/include/asm/processor.h:796
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff831c4b45)
Location: arch/x86/include/asm/processor.h:796
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff831cfa90)
Location: arch/x86/include/asm/processor.h:796
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_detect
```
```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/include/asm/processor.h:796
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In arch/x86/kernel/jailhouse.c (ffffffff81081261)
Location: arch/x86/include/asm/processor.h:796
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: arch/x86/include/asm/processor.h:796
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_request_version
```
```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: arch/x86/include/asm/processor.h:796
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81754958)
Location: arch/x86/include/asm/processor.h:796
Inline: True
```
```
In arch/x86/pci/xen.c (ffffffff8322bcb2)
Location: arch/x86/include/asm/processor.h:796
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_hvm_msi_init
```
**Symbols:**

```
ffffffff81bc4a5c-ffffffff81bc4af1: hypervisor_cpuid_base.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff81c970f1)
Location: arch/x86/include/asm/processor.h:811
Inline: True
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_platform_hvm
  - arch/x86/xen/enlighten_hvm.c:xen_parse_nopv
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff832a2911)
Location: arch/x86/include/asm/processor.h:811
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff832a4b24)
Location: arch/x86/include/asm/processor.h:811
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff832a579e)
Location: arch/x86/include/asm/processor.h:811
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff832b1f1f)
Location: arch/x86/include/asm/processor.h:811
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_detect
```
```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/include/asm/processor.h:811
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In arch/x86/kernel/jailhouse.c (ffffffff81090211)
Location: arch/x86/include/asm/processor.h:811
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: arch/x86/include/asm/processor.h:811
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_request_version
```
```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: arch/x86/include/asm/processor.h:811
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff817d8018)
Location: arch/x86/include/asm/processor.h:811
Inline: True
```
```
In arch/x86/pci/xen.c (ffffffff833164d7)
Location: arch/x86/include/asm/processor.h:811
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_hvm_msi_init
```
**Symbols:**

```
ffffffff81c970f1-ffffffff81c97186: hypervisor_cpuid_base.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff81e4651d)
Location: arch/x86/include/asm/processor.h:814
Inline: True
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_platform_hvm
  - arch/x86/xen/enlighten_hvm.c:msi_ext_dest_id
  - arch/x86/xen/enlighten_hvm.c:xen_parse_nopv
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff83451c9c)
Location: arch/x86/include/asm/processor.h:814
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff83453ce3)
Location: arch/x86/include/asm/processor.h:814
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff834547e0)
Location: arch/x86/include/asm/processor.h:814
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff83463213)
Location: arch/x86/include/asm/processor.h:814
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_detect
```
```
In arch/x86/kernel/kvm.c (ffffffff8109ee48)
Location: arch/x86/include/asm/processor.h:814
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In arch/x86/kernel/jailhouse.c (ffffffff810a1111)
Location: arch/x86/include/asm/processor.h:814
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff818c8a6a)
Location: arch/x86/include/asm/processor.h:814
Inline: True
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff818d691c)
Location: arch/x86/include/asm/processor.h:814
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81916285)
Location: arch/x86/include/asm/processor.h:814
Inline: True
```
```
In arch/x86/pci/xen.c (ffffffff834d0e4f)
Location: arch/x86/include/asm/processor.h:814
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_hvm_msi_init
```
**Symbols:**

```
ffffffff81e4651d-ffffffff81e465c3: hypervisor_cpuid_base.constprop.0 (STB_LOCAL)
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
Location: arch/x86/include/asm/cpuid.h:156
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_platform_hvm
  - arch/x86/xen/enlighten_hvm.c:msi_ext_dest_id
  - arch/x86/xen/enlighten_hvm.c:xen_parse_nopv
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff83e6e94c)
Location: arch/x86/include/asm/cpuid.h:156
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff83e71472)
Location: arch/x86/include/asm/cpuid.h:156
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff83e72291)
Location: arch/x86/include/asm/cpuid.h:156
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff83e85c34)
Location: arch/x86/include/asm/cpuid.h:156
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_detect
```
```
In arch/x86/kernel/kvm.c (ffffffff810b68e8)
Location: arch/x86/include/asm/cpuid.h:156
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In arch/x86/kernel/jailhouse.c (ffffffff810b9021)
Location: arch/x86/include/asm/cpuid.h:156
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff81a19838)
Location: arch/x86/include/asm/cpuid.h:156
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_request_version
```
```
In drivers/xen/events/events_base.c (ffffffff83eea886)
Location: arch/x86/include/asm/cpuid.h:156
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_setup_upcall_vector
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81a28e72)
Location: arch/x86/include/asm/cpuid.h:156
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81a719a5)
Location: arch/x86/include/asm/cpuid.h:156
Inline: True
```
```
In arch/x86/pci/xen.c (ffffffff83f14fc3)
Location: arch/x86/include/asm/cpuid.h:156
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
Location: arch/x86/include/asm/cpuid.h:156
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff8368c391)
Location: arch/x86/include/asm/cpuid.h:156
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_platform_hvm
  - arch/x86/xen/enlighten_hvm.c:msi_ext_dest_id
  - arch/x86/xen/enlighten_hvm.c:xen_parse_nopv
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8368f2cc)
Location: arch/x86/include/asm/cpuid.h:156
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff836922c1)
Location: arch/x86/include/asm/cpuid.h:156
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff836931a1)
Location: arch/x86/include/asm/cpuid.h:156
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff836a9174)
Location: arch/x86/include/asm/cpuid.h:156
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_detect
```
```
In arch/x86/kernel/kvm.c (ffffffff810b9a28)
Location: arch/x86/include/asm/cpuid.h:156
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In arch/x86/kernel/jailhouse.c (ffffffff810bc1f1)
Location: arch/x86/include/asm/cpuid.h:156
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff81a628b8)
Location: arch/x86/include/asm/cpuid.h:156
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_request_version
```
```
In drivers/xen/events/events_base.c (ffffffff83710276)
Location: arch/x86/include/asm/cpuid.h:156
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_setup_upcall_vector
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81a72572)
Location: arch/x86/include/asm/cpuid.h:156
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81abc255)
Location: arch/x86/include/asm/cpuid.h:156
Inline: True
```
```
In arch/x86/pci/xen.c (ffffffff8373b743)
Location: arch/x86/include/asm/cpuid.h:156
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
Location: arch/x86/include/asm/cpuid.h:156
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff838bbf51)
Location: arch/x86/include/asm/cpuid.h:156
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_platform_hvm
  - arch/x86/xen/enlighten_hvm.c:msi_ext_dest_id
  - arch/x86/xen/enlighten_hvm.c:xen_parse_nopv
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff838bf12c)
Location: arch/x86/include/asm/cpuid.h:156
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff838c1dd1)
Location: arch/x86/include/asm/cpuid.h:156
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff838c2d11)
Location: arch/x86/include/asm/cpuid.h:156
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff838d97d4)
Location: arch/x86/include/asm/cpuid.h:156
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_detect
```
```
In arch/x86/kernel/kvm.c (ffffffff810c10c8)
Location: arch/x86/include/asm/cpuid.h:156
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In arch/x86/kernel/jailhouse.c (ffffffff810c3371)
Location: arch/x86/include/asm/cpuid.h:156
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff81ab5818)
Location: arch/x86/include/asm/cpuid.h:156
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_request_version
```
```
In drivers/xen/events/events_base.c (ffffffff83943bf6)
Location: arch/x86/include/asm/cpuid.h:156
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_setup_upcall_vector
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81ac46d2)
Location: arch/x86/include/asm/cpuid.h:156
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81b0efa5)
Location: arch/x86/include/asm/cpuid.h:156
Inline: True
```
```
In arch/x86/pci/xen.c (ffffffff839700ce)
Location: arch/x86/include/asm/cpuid.h:156
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
<summary>In <code>aws</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff8101ee0e)
Location: arch/x86/include/asm/processor.h:944
Inline: True
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_platform_hvm
  - arch/x86/xen/enlighten_hvm.c:xen_parse_nopv
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: arch/x86/include/asm/processor.h:944
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff82895706)
Location: arch/x86/include/asm/processor.h:944
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff82896e09)
Location: arch/x86/include/asm/processor.h:944
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff828a1cdb)
Location: arch/x86/include/asm/processor.h:944
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_detect
```
```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/include/asm/processor.h:944
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In arch/x86/kernel/jailhouse.c (ffffffff81078410)
Location: arch/x86/include/asm/processor.h:944
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_paravirt
Direct callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_detect
```
```
In drivers/xen/grant-table.c (0)
Location: arch/x86/include/asm/processor.h:944
Inline: True
```
```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: arch/x86/include/asm/processor.h:944
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81669123)
Location: arch/x86/include/asm/processor.h:944
Inline: True
```
```
In arch/x86/pci/xen.c (0)
Location: arch/x86/include/asm/processor.h:944
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_msi_init
```
**Symbols:**

```
ffffffff8101ee0e-ffffffff8101eebe: hypervisor_cpuid_base.constprop.0 (STB_LOCAL)
ffffffff81078410-ffffffff810784b8: hypervisor_cpuid_base.constprop.0 (STB_LOCAL)
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
In arch/x86/platform/pvh/enlighten.c (ffffffff8288f142)
Location: arch/x86/include/asm/processor.h:944
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff82899e29)
Location: arch/x86/include/asm/processor.h:944
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_detect
```
```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/include/asm/processor.h:944
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In arch/x86/kernel/jailhouse.c (ffffffff81067ce3)
Location: arch/x86/include/asm/processor.h:944
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff8101ec6a)
Location: arch/x86/include/asm/processor.h:944
Inline: True
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_platform_hvm
  - arch/x86/xen/enlighten_hvm.c:xen_parse_nopv
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: arch/x86/include/asm/processor.h:944
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff828a86f6)
Location: arch/x86/include/asm/processor.h:944
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff828a9df9)
Location: arch/x86/include/asm/processor.h:944
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/include/asm/processor.h:944
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In arch/x86/kernel/jailhouse.c (ffffffff810783c0)
Location: arch/x86/include/asm/processor.h:944
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_paravirt
Direct callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_detect
```
```
In drivers/xen/grant-table.c (0)
Location: arch/x86/include/asm/processor.h:944
Inline: True
```
```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: arch/x86/include/asm/processor.h:944
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81697503)
Location: arch/x86/include/asm/processor.h:944
Inline: True
```
```
In arch/x86/pci/xen.c (0)
Location: arch/x86/include/asm/processor.h:944
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_msi_init
```
**Symbols:**

```
ffffffff8101ec6a-ffffffff8101ed1a: hypervisor_cpuid_base.constprop.0 (STB_LOCAL)
ffffffff810783c0-ffffffff81078468: hypervisor_cpuid_base.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff8101eeba)
Location: arch/x86/include/asm/processor.h:944
Inline: True
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_platform_hvm
  - arch/x86/xen/enlighten_hvm.c:xen_parse_nopv
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/xen/enlighten_pv.c (0)
Location: arch/x86/include/asm/processor.h:944
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_platform_pv
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff828a8706)
Location: arch/x86/include/asm/processor.h:944
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/platform/pvh/enlighten.c (ffffffff828a9e09)
Location: arch/x86/include/asm/processor.h:944
Inline: True
Inline callers:
  - arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff828b4cbf)
Location: arch/x86/include/asm/processor.h:944
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_detect
```
```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/include/asm/processor.h:944
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__kvm_cpuid_base
```
```
In arch/x86/kernel/jailhouse.c (ffffffff8107a4c0)
Location: arch/x86/include/asm/processor.h:944
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_paravirt
Direct callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_detect
```
```
In drivers/xen/grant-table.c (0)
Location: arch/x86/include/asm/processor.h:944
Inline: True
```
```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: arch/x86/include/asm/processor.h:944
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816b1bc3)
Location: arch/x86/include/asm/processor.h:944
Inline: True
```
```
In arch/x86/pci/xen.c (0)
Location: arch/x86/include/asm/processor.h:944
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_msi_init
```
**Symbols:**

```
ffffffff8101eeba-ffffffff8101ef6a: hypervisor_cpuid_base.constprop.0 (STB_LOCAL)
ffffffff8107a4c0-ffffffff8107a568: hypervisor_cpuid_base.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
