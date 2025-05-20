# Function: <code>ghcb_rdx_is_valid</code>

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
In arch/x86/kernel/cpu/vmware.c (ffffffff81069431)
Location: arch/x86/include/asm/svm.h:422
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_finish
```
```
In arch/x86/kernel/sev-es.c (ffffffff81083f97)
Location: arch/x86/include/asm/svm.h:422
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
In arch/x86/kernel/cpu/vmware.c (ffffffff81069eb1)
Location: arch/x86/include/asm/svm.h:426
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_finish
```
```
In arch/x86/kernel/sev.c (ffffffff81084604)
Location: arch/x86/include/asm/svm.h:426
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
In arch/x86/kernel/cpu/vmware.c (ffffffff81074541)
Location: arch/x86/include/asm/svm.h:431
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_finish
```
```
In arch/x86/kernel/sev.c (ffffffff810937c4)
Location: arch/x86/include/asm/svm.h:431
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
In arch/x86/kernel/cpu/vmware.c (ffffffff81082db1)
Location: arch/x86/include/asm/svm.h:600
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_finish
```
```
In arch/x86/kernel/sev.c (ffffffff810a5a4e)
Location: arch/x86/include/asm/svm.h:600
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
In arch/x86/kernel/cpu/vmware.c (ffffffff810958c1)
Location: arch/x86/include/asm/svm.h:652
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_finish
```
```
In arch/x86/kernel/sev.c (ffffffff810be2b4)
Location: arch/x86/include/asm/svm.h:652
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
In arch/x86/kernel/cpu/vmware.c (ffffffff81098831)
Location: arch/x86/include/asm/svm.h:662
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_finish
```
```
In arch/x86/kernel/sev.c (ffffffff810c19bf)
Location: arch/x86/include/asm/svm.h:662
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
In arch/x86/kernel/cpu/vmware.c (ffffffff8109fdd1)
Location: arch/x86/include/asm/svm.h:658
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_finish
```
```
In arch/x86/kernel/sev.c (ffffffff810c8e57)
Location: arch/x86/include/asm/svm.h:658
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
