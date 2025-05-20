# Function: <code>ghcb_set_rbx</code>

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
In arch/x86/kernel/cpu/vmware.c (ffffffff8106936d)
Location: arch/x86/include/asm/svm.h:423
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
```
```
In arch/x86/kernel/kvm.c (ffffffff8107e2ca)
Location: arch/x86/include/asm/svm.h:423
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
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
In arch/x86/kernel/cpu/vmware.c (ffffffff81069e06)
Location: arch/x86/include/asm/svm.h:427
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
```
```
In arch/x86/kernel/kvm.c (ffffffff8107f3da)
Location: arch/x86/include/asm/svm.h:427
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
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
In arch/x86/kernel/cpu/vmware.c (ffffffff81074496)
Location: arch/x86/include/asm/svm.h:432
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
```
```
In arch/x86/kernel/kvm.c (ffffffff8108e13a)
Location: arch/x86/include/asm/svm.h:432
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
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
In arch/x86/kernel/cpu/vmware.c (ffffffff81082cf6)
Location: arch/x86/include/asm/svm.h:601
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
```
```
In arch/x86/kernel/kvm.c (ffffffff8109e93a)
Location: arch/x86/include/asm/svm.h:601
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
```
```
In arch/x86/kernel/sev.c (ffffffff810a3d38)
Location: arch/x86/include/asm/svm.h:601
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:snp_issue_guest_request
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
In arch/x86/kernel/cpu/vmware.c (ffffffff810957f6)
Location: arch/x86/include/asm/svm.h:653
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
```
```
In arch/x86/kernel/kvm.c (ffffffff810b60ba)
Location: arch/x86/include/asm/svm.h:653
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
```
```
In arch/x86/kernel/sev.c (ffffffff810bc1be)
Location: arch/x86/include/asm/svm.h:653
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:snp_issue_guest_request
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
In arch/x86/kernel/cpu/vmware.c (ffffffff81098766)
Location: arch/x86/include/asm/svm.h:663
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
```
```
In arch/x86/kernel/kvm.c (ffffffff810b91ba)
Location: arch/x86/include/asm/svm.h:663
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
```
```
In arch/x86/kernel/sev.c (ffffffff810bf3f8)
Location: arch/x86/include/asm/svm.h:663
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:snp_issue_guest_request
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
In arch/x86/kernel/cpu/vmware.c (ffffffff8109fd06)
Location: arch/x86/include/asm/svm.h:659
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
```
```
In arch/x86/kernel/kvm.c (ffffffff810c05fa)
Location: arch/x86/include/asm/svm.h:659
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
```
```
In arch/x86/kernel/sev.c (ffffffff810c6748)
Location: arch/x86/include/asm/svm.h:659
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:snp_issue_guest_request
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
