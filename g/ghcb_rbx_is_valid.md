# Function: <code>ghcb_rbx_is_valid</code>

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
In arch/x86/kernel/cpu/vmware.c (ffffffff81069405)
Location: arch/x86/include/asm/svm.h:423
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_finish
```
```
In arch/x86/kernel/sev-es.c (ffffffff810825dc)
Location: arch/x86/include/asm/svm.h:423
Inline: True
Inline callers:
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
In arch/x86/kernel/cpu/vmware.c (ffffffff81069e85)
Location: arch/x86/include/asm/svm.h:427
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_finish
```
```
In arch/x86/kernel/sev.c (ffffffff8108492e)
Location: arch/x86/include/asm/svm.h:427
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
In arch/x86/kernel/cpu/vmware.c (ffffffff81074515)
Location: arch/x86/include/asm/svm.h:432
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_finish
```
```
In arch/x86/kernel/sev.c (ffffffff81093aee)
Location: arch/x86/include/asm/svm.h:432
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
In arch/x86/kernel/cpu/vmware.c (ffffffff81082d85)
Location: arch/x86/include/asm/svm.h:601
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_finish
```
```
In arch/x86/kernel/sev.c (ffffffff810a5d5a)
Location: arch/x86/include/asm/svm.h:601
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
In arch/x86/kernel/cpu/vmware.c (ffffffff81095895)
Location: arch/x86/include/asm/svm.h:653
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_finish
```
```
In arch/x86/kernel/sev.c (ffffffff810bd386)
Location: arch/x86/include/asm/svm.h:653
Inline: True
Inline callers:
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
In arch/x86/kernel/cpu/vmware.c (ffffffff81098805)
Location: arch/x86/include/asm/svm.h:663
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_finish
```
```
In arch/x86/kernel/sev.c (ffffffff810c09f9)
Location: arch/x86/include/asm/svm.h:663
Inline: True
Inline callers:
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
In arch/x86/kernel/cpu/vmware.c (ffffffff8109fda5)
Location: arch/x86/include/asm/svm.h:659
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_finish
```
```
In arch/x86/kernel/sev.c (ffffffff810c7e59)
Location: arch/x86/include/asm/svm.h:659
Inline: True
Inline callers:
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
