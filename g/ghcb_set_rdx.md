# Function: <code>ghcb_set_rdx</code>

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
In arch/x86/kernel/cpu/vmware.c (ffffffff8106939d)
Location: arch/x86/include/asm/svm.h:422
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
```
```
In arch/x86/kernel/kvm.c (ffffffff8107e302)
Location: arch/x86/include/asm/svm.h:422
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
```
```
In arch/x86/kernel/sev-es.c (ffffffff810841ee)
Location: arch/x86/include/asm/svm.h:422
Inline: True
Inline callers:
  - arch/x86/kernel/sev-es.c:vc_handle_exitcode
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
In arch/x86/kernel/cpu/vmware.c (ffffffff81069e2e)
Location: arch/x86/include/asm/svm.h:426
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
```
```
In arch/x86/kernel/kvm.c (ffffffff8107f411)
Location: arch/x86/include/asm/svm.h:426
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
```
```
In arch/x86/kernel/sev.c (ffffffff81084ab0)
Location: arch/x86/include/asm/svm.h:426
Inline: True
Inline callers:
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
In arch/x86/kernel/cpu/vmware.c (ffffffff810744be)
Location: arch/x86/include/asm/svm.h:431
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
```
```
In arch/x86/kernel/kvm.c (ffffffff8108e171)
Location: arch/x86/include/asm/svm.h:431
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
```
```
In arch/x86/kernel/sev.c (ffffffff81093c70)
Location: arch/x86/include/asm/svm.h:431
Inline: True
Inline callers:
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
In arch/x86/hyperv/ivm.c (ffffffff8103ef4d)
Location: arch/x86/include/asm/svm.h:600
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff81082d1e)
Location: arch/x86/include/asm/svm.h:600
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
```
```
In arch/x86/kernel/kvm.c (ffffffff8109e971)
Location: arch/x86/include/asm/svm.h:600
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
```
```
In arch/x86/kernel/sev.c (ffffffff810a5ef5)
Location: arch/x86/include/asm/svm.h:600
Inline: True
Inline callers:
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
In arch/x86/hyperv/ivm.c (ffffffff81047ff2)
Location: arch/x86/include/asm/svm.h:652
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff8109581e)
Location: arch/x86/include/asm/svm.h:652
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
```
```
In arch/x86/kernel/kvm.c (ffffffff810b60f1)
Location: arch/x86/include/asm/svm.h:652
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
```
```
In arch/x86/kernel/sev.c (ffffffff810be625)
Location: arch/x86/include/asm/svm.h:652
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:vc_handle_exitcode
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
In arch/x86/hyperv/ivm.c (ffffffff810483a2)
Location: arch/x86/include/asm/svm.h:662
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff8109878e)
Location: arch/x86/include/asm/svm.h:662
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
```
```
In arch/x86/kernel/kvm.c (ffffffff810b91f1)
Location: arch/x86/include/asm/svm.h:662
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
```
```
In arch/x86/kernel/sev.c (ffffffff810c1c8d)
Location: arch/x86/include/asm/svm.h:662
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:vc_handle_exitcode
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
In arch/x86/hyperv/ivm.c (ffffffff8104ed82)
Location: arch/x86/include/asm/svm.h:658
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff8109fd2e)
Location: arch/x86/include/asm/svm.h:658
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff810a02dd)
Location: arch/x86/include/asm/svm.h:658
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_sev_es_hcall_prepare
```
```
In arch/x86/kernel/kvm.c (ffffffff810c0631)
Location: arch/x86/include/asm/svm.h:658
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
```
```
In arch/x86/kernel/sev.c (ffffffff810c9171)
Location: arch/x86/include/asm/svm.h:658
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:vc_handle_exitcode
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
