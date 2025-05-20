# Function: <code>pte_mfn</code>

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
In arch/x86/xen/mmu.c (0)
Location: arch/x86/include/asm/xen/page.h:255
Inline: True
```
```
In arch/x86/xen/p2m.c (ffffffff81025426)
Location: arch/x86/include/asm/xen/page.h:255
Inline: True
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
In arch/x86/xen/mmu.c (0)
Location: arch/x86/include/asm/xen/page.h:255
Inline: True
```
```
In arch/x86/xen/p2m.c (ffffffff81891e9e)
Location: arch/x86/include/asm/xen/page.h:255
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
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
In arch/x86/xen/mmu.c (0)
Location: arch/x86/include/asm/xen/page.h:255
Inline: True
```
```
In arch/x86/xen/p2m.c (ffffffff818c67be)
Location: arch/x86/include/asm/xen/page.h:255
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
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
In arch/x86/xen/mmu.c (0)
Location: arch/x86/include/asm/xen/page.h:281
Inline: True
```
```
In arch/x86/xen/p2m.c (ffffffff818fdea8)
Location: arch/x86/include/asm/xen/page.h:281
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
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
In arch/x86/xen/mmu.c (ffffffff8101ad67)
Location: arch/x86/include/asm/xen/page.h:288
Inline: True
```
```
In arch/x86/xen/p2m.c (ffffffff81987ee4)
Location: arch/x86/include/asm/xen/page.h:288
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
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
In arch/x86/xen/mmu.c (ffffffff8101b74e)
Location: arch/x86/include/asm/xen/page.h:288
Inline: True
```
```
In arch/x86/xen/p2m.c (ffffffff819e4876)
Location: arch/x86/include/asm/xen/page.h:288
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
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
In arch/x86/xen/mmu.c (ffffffff8101b9be)
Location: arch/x86/include/asm/xen/page.h:315
Inline: True
```
```
In arch/x86/xen/p2m.c (ffffffff81a1f9a6)
Location: arch/x86/include/asm/xen/page.h:315
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
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
In arch/x86/xen/mmu.c (ffffffff8101d501)
Location: arch/x86/include/asm/xen/page.h:315
Inline: True
```
```
In arch/x86/xen/p2m.c (ffffffff81a90196)
Location: arch/x86/include/asm/xen/page.h:315
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
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
In arch/x86/xen/mmu.c (ffffffff8101dea1)
Location: arch/x86/include/asm/xen/page.h:315
Inline: True
```
```
In arch/x86/xen/p2m.c (ffffffff81ac7526)
Location: arch/x86/include/asm/xen/page.h:315
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
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
In arch/x86/xen/mmu.c (ffffffff81020261)
Location: arch/x86/include/asm/xen/page.h:314
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
```
```
In arch/x86/xen/p2m.c (ffffffff81bbffa4)
Location: arch/x86/include/asm/xen/page.h:314
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
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
In arch/x86/xen/mmu.c (ffffffff81020c91)
Location: arch/x86/include/asm/xen/page.h:314
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
```
```
In arch/x86/xen/p2m.c (ffffffff81c38f74)
Location: arch/x86/include/asm/xen/page.h:314
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
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
In arch/x86/xen/mmu.c (ffffffff8102302e)
Location: arch/x86/include/asm/xen/page.h:314
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
```
```
In arch/x86/xen/p2m.c (ffffffff8102672b)
Location: arch/x86/include/asm/xen/page.h:314
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
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
In arch/x86/xen/mmu.c (ffffffff8102719e)
Location: arch/x86/include/asm/xen/page.h:314
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
```
```
In arch/x86/xen/p2m.c (ffffffff8102ac3b)
Location: arch/x86/include/asm/xen/page.h:314
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
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
In arch/x86/xen/mmu.c (ffffffff8102b374)
Location: arch/x86/include/asm/xen/page.h:306
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
```
```
In arch/x86/xen/p2m.c (ffffffff8102f69c)
Location: arch/x86/include/asm/xen/page.h:306
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
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
In arch/x86/xen/mmu.c (ffffffff81032094)
Location: arch/x86/include/asm/xen/page.h:306
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
```
```
In arch/x86/xen/p2m.c (ffffffff81036a2c)
Location: arch/x86/include/asm/xen/page.h:306
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
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
In arch/x86/xen/mmu.c (ffffffff81032094)
Location: arch/x86/include/asm/xen/page.h:306
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
```
```
In arch/x86/xen/p2m.c (ffffffff8103699c)
Location: arch/x86/include/asm/xen/page.h:306
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
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
In arch/x86/xen/mmu.c (ffffffff81038384)
Location: arch/x86/include/asm/xen/page.h:309
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
```
```
In arch/x86/xen/p2m.c (ffffffff8103cb9c)
Location: arch/x86/include/asm/xen/page.h:309
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:set_foreign_p2m_mapping
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
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
In arch/x86/xen/mmu.c (ffffffff8101dea1)
Location: arch/x86/include/asm/xen/page.h:315
Inline: True
```
```
In arch/x86/xen/p2m.c (ffffffff81a66396)
Location: arch/x86/include/asm/xen/page.h:315
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101de61)
Location: arch/x86/include/asm/xen/page.h:315
Inline: True
```
```
In arch/x86/xen/p2m.c (ffffffff81ad27a6)
Location: arch/x86/include/asm/xen/page.h:315
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
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
In arch/x86/xen/mmu.c (ffffffff8101e0b1)
Location: arch/x86/include/asm/xen/page.h:315
Inline: True
```
```
In arch/x86/xen/p2m.c (ffffffff81adeca6)
Location: arch/x86/include/asm/xen/page.h:315
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
```
</details>
</li>
</ul>

## Differences
