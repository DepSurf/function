# Function: <code>ghcb_set_sw_scratch</code>

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
In arch/x86/kernel/sev-es.c (ffffffff81083858)
Location: arch/x86/include/asm/svm.h:438
Inline: True
Inline callers:
  - arch/x86/kernel/sev-es.c:vc_do_mmio
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
In arch/x86/kernel/sev.c (ffffffff81083ddf)
Location: arch/x86/include/asm/svm.h:442
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:vc_do_mmio
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
In arch/x86/kernel/sev.c (ffffffff81092f9f)
Location: arch/x86/include/asm/svm.h:447
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:vc_do_mmio
  - arch/x86/kernel/sev.c:vc_handle_ioio
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810a5515)
Location: arch/x86/include/asm/svm.h:616
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:vc_do_mmio
  - arch/x86/kernel/sev.c:vmgexit_psc
  - arch/x86/kernel/sev.c:vc_handle_ioio
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810bdc65)
Location: arch/x86/include/asm/svm.h:668
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:vc_do_mmio
  - arch/x86/kernel/sev.c:vmgexit_psc
  - arch/x86/kernel/sev.c:vc_handle_ioio
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810c12d5)
Location: arch/x86/include/asm/svm.h:678
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:vc_do_mmio
  - arch/x86/kernel/sev.c:vmgexit_psc
  - arch/x86/kernel/sev.c:vc_handle_ioio
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810c8735)
Location: arch/x86/include/asm/svm.h:674
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:vc_do_mmio
  - arch/x86/kernel/sev.c:vmgexit_psc
  - arch/x86/kernel/sev.c:vc_handle_ioio
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
