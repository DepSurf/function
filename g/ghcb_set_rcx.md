# Function: <code>ghcb_set_rcx</code>

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
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/vmware.c (ffffffff81069385)
Location: arch/x86/include/asm/svm.h:421
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
```
```
In arch/x86/kernel/kvm.c (ffffffff8107e2ea)
Location: arch/x86/include/asm/svm.h:421
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
```
```
In arch/x86/kernel/sev-es.c (ffffffff8108400d)
Location: arch/x86/include/asm/svm.h:421
Inline: True
Inline callers:
  - arch/x86/kernel/sev-es.c:vc_handle_exitcode
  - arch/x86/kernel/sev-es.c:vc_handle_exitcode
  - arch/x86/kernel/sev-es.c:vc_handle_cpuid
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
In arch/x86/kernel/cpu/vmware.c (ffffffff81069e1a)
Location: arch/x86/include/asm/svm.h:425
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
```
```
In arch/x86/kernel/kvm.c (ffffffff8107f3fd)
Location: arch/x86/include/asm/svm.h:425
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
```
```
In arch/x86/kernel/sev.c (ffffffff81084682)
Location: arch/x86/include/asm/svm.h:425
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
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
In arch/x86/kernel/cpu/vmware.c (ffffffff810744aa)
Location: arch/x86/include/asm/svm.h:430
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
```
```
In arch/x86/kernel/kvm.c (ffffffff8108e15d)
Location: arch/x86/include/asm/svm.h:430
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
```
```
In arch/x86/kernel/sev.c (ffffffff81093842)
Location: arch/x86/include/asm/svm.h:430
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
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
In arch/x86/hyperv/ivm.c (ffffffff8103ee04)
Location: arch/x86/include/asm/svm.h:599
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_read
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff81082d0a)
Location: arch/x86/include/asm/svm.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
```
```
In arch/x86/kernel/kvm.c (ffffffff8109e95d)
Location: arch/x86/include/asm/svm.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
```
```
In arch/x86/kernel/sev.c (ffffffff810a5aa8)
Location: arch/x86/include/asm/svm.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
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
In arch/x86/hyperv/ivm.c (ffffffff81047ecc)
Location: arch/x86/include/asm/svm.h:651
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_read
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff8109580a)
Location: arch/x86/include/asm/svm.h:651
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
```
```
In arch/x86/kernel/kvm.c (ffffffff810b60dd)
Location: arch/x86/include/asm/svm.h:651
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
```
```
In arch/x86/kernel/sev.c (ffffffff810be311)
Location: arch/x86/include/asm/svm.h:651
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_cpuid
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
In arch/x86/hyperv/ivm.c (ffffffff8104827c)
Location: arch/x86/include/asm/svm.h:661
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_read
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff8109877a)
Location: arch/x86/include/asm/svm.h:661
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
```
```
In arch/x86/kernel/kvm.c (ffffffff810b91dd)
Location: arch/x86/include/asm/svm.h:661
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
```
```
In arch/x86/kernel/sev.c (ffffffff810c1915)
Location: arch/x86/include/asm/svm.h:661
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_cpuid
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
In arch/x86/hyperv/ivm.c (ffffffff8104ec5c)
Location: arch/x86/include/asm/svm.h:657
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_read
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff8109fd1a)
Location: arch/x86/include/asm/svm.h:657
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff810a02ba)
Location: arch/x86/include/asm/svm.h:657
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_sev_es_hcall_prepare
```
```
In arch/x86/kernel/kvm.c (ffffffff810c061d)
Location: arch/x86/include/asm/svm.h:657
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
```
```
In arch/x86/kernel/sev.c (ffffffff810c8da9)
Location: arch/x86/include/asm/svm.h:657
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_cpuid
  - arch/x86/kernel/sev.c:__sev_cpuid_hv_ghcb
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
