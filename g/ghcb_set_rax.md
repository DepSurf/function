# Function: <code>ghcb_set_rax</code>

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
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev-es.c (ffffffff810841d1)
Location: arch/x86/include/asm/svm.h:420
Inline: True
Inline callers:
  - arch/x86/kernel/sev-es.c:vc_handle_exitcode
  - arch/x86/kernel/sev-es.c:vc_handle_vmmcall
  - arch/x86/kernel/sev-es.c:vc_handle_dr7_write
  - arch/x86/kernel/sev-es.c:vc_handle_cpuid
  - arch/x86/kernel/sev-es.c:vc_handle_ioio
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
In arch/x86/kernel/sev.c (ffffffff81084860)
Location: arch/x86/include/asm/svm.h:424
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_ioio
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
In arch/x86/kernel/sev.c (ffffffff81093a20)
Location: arch/x86/include/asm/svm.h:429
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_ioio
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
In arch/x86/hyperv/ivm.c (ffffffff8103ef40)
Location: arch/x86/include/asm/svm.h:598
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
```
```
In arch/x86/kernel/sev.c (ffffffff810a3d20)
Location: arch/x86/include/asm/svm.h:598
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:snp_issue_guest_request
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:vc_handle_ioio
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
In arch/x86/hyperv/ivm.c (ffffffff81047fe4)
Location: arch/x86/include/asm/svm.h:650
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
```
```
In arch/x86/kernel/sev.c (ffffffff810bc1a6)
Location: arch/x86/include/asm/svm.h:650
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:snp_issue_guest_request
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:vc_handle_cpuid
  - arch/x86/kernel/sev.c:vc_handle_ioio
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
In arch/x86/hyperv/ivm.c (ffffffff81048394)
Location: arch/x86/include/asm/svm.h:660
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
```
```
In arch/x86/kernel/sev.c (ffffffff810bf3df)
Location: arch/x86/include/asm/svm.h:660
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:snp_issue_guest_request
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:vc_handle_cpuid
  - arch/x86/kernel/sev.c:vc_handle_ioio
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
In arch/x86/hyperv/ivm.c (ffffffff8104ed74)
Location: arch/x86/include/asm/svm.h:656
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
```
```
In arch/x86/kernel/sev.c (ffffffff810c672f)
Location: arch/x86/include/asm/svm.h:656
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:snp_issue_guest_request
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:vc_handle_cpuid
  - arch/x86/kernel/sev.c:vc_handle_ioio
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
