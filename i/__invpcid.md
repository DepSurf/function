# Function: <code>__invpcid</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81064596)
Location: arch/x86/include/asm/tlbflush.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_global
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81067a76)
Location: arch/x86/include/asm/tlbflush.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_global
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81066d00)
Location: arch/x86/include/asm/tlbflush.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_global
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8106b21d)
Location: arch/x86/include/asm/invpcid.h:5
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb_global
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8106de90)
Location: arch/x86/include/asm/invpcid.h:5
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb_global
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81073e20)
Location: arch/x86/include/asm/invpcid.h:5
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb_global
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810779c0)
Location: arch/x86/include/asm/invpcid.h:5
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb_global
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81078a30)
Location: arch/x86/include/asm/invpcid.h:5
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb_global
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108b964)
Location: arch/x86/include/asm/invpcid.h:5
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_global
  - arch/x86/mm/tlb.c:native_flush_tlb_one_user
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108b9b4)
Location: arch/x86/include/asm/invpcid.h:5
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_global
  - arch/x86/mm/tlb.c:native_flush_tlb_one_user
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
In arch/x86/mm/tlb.c (ffffffff8108c5b9)
Location: arch/x86/include/asm/invpcid.h:5
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_global
  - arch/x86/mm/tlb.c:native_flush_tlb_one_user
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
In arch/x86/mm/tlb.c (ffffffff8109bdf9)
Location: arch/x86/include/asm/invpcid.h:5
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_global
  - arch/x86/mm/tlb.c:native_flush_tlb_one_user
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
In arch/x86/mm/tlb.c (ffffffff810af339)
Location: arch/x86/include/asm/invpcid.h:5
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_global
  - arch/x86/mm/tlb.c:native_flush_tlb_one_user
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
In arch/x86/mm/tlb.c (ffffffff810c9769)
Location: arch/x86/include/asm/invpcid.h:5
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_global
  - arch/x86/mm/tlb.c:native_flush_tlb_one_user
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
In arch/x86/mm/tlb.c (ffffffff810ccde9)
Location: arch/x86/include/asm/invpcid.h:5
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_global
  - arch/x86/mm/tlb.c:native_flush_tlb_one_user
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
In arch/x86/mm/tlb.c (ffffffff810d54b9)
Location: arch/x86/include/asm/invpcid.h:5
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_global
  - arch/x86/mm/tlb.c:native_flush_tlb_one_user
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81077a30)
Location: arch/x86/include/asm/invpcid.h:5
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb_global
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
In arch/x86/kernel/paravirt.c (ffffffff81067710)
Location: arch/x86/include/asm/invpcid.h:5
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb_global
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810779e0)
Location: arch/x86/include/asm/invpcid.h:5
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb_global
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81079a80)
Location: arch/x86/include/asm/invpcid.h:5
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb_global
```
</details>
</li>
</ul>

## Differences
