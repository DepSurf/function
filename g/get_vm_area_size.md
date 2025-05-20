# Function: <code>get_vm_area_size</code>

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
In arch/x86/mm/ioremap.c (ffffffff8106be03)
Location: include/linux/vmalloc.h:101
Inline: True
```
```
In mm/vmalloc.c (ffffffff811ce201)
Location: include/linux/vmalloc.h:101
Inline: True
Inline callers:
  - mm/vmalloc.c:map_vm_area
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vwrite
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
In arch/x86/mm/ioremap.c (ffffffff8106bcdd)
Location: include/linux/vmalloc.h:102
Inline: True
```
```
In mm/vmalloc.c (ffffffff811ecc54)
Location: include/linux/vmalloc.h:102
Inline: True
Inline callers:
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:map_vm_area
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
In arch/x86/mm/ioremap.c (ffffffff8106f8fd)
Location: include/linux/vmalloc.h:103
Inline: True
```
```
In mm/vmalloc.c (ffffffff811fdee5)
Location: include/linux/vmalloc.h:103
Inline: True
Inline callers:
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/vmalloc.c:map_vm_area
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
In arch/x86/mm/ioremap.c (ffffffff8106f01d)
Location: include/linux/vmalloc.h:114
Inline: True
```
```
In mm/vmalloc.c (ffffffff81208acc)
Location: include/linux/vmalloc.h:114
Inline: True
Inline callers:
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:map_vm_area
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
In arch/x86/mm/ioremap.c (ffffffff8107410d)
Location: include/linux/vmalloc.h:115
Inline: True
```
```
In mm/vmalloc.c (ffffffff81221beb)
Location: include/linux/vmalloc.h:115
Inline: True
Inline callers:
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:map_vm_area
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
In arch/x86/mm/ioremap.c (ffffffff81076b21)
Location: include/linux/vmalloc.h:116
Inline: True
```
```
In mm/vmalloc.c (ffffffff81243acb)
Location: include/linux/vmalloc.h:116
Inline: True
Inline callers:
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:map_vm_area
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
In arch/x86/mm/ioremap.c (ffffffff8107d1b1)
Location: include/linux/vmalloc.h:116
Inline: True
```
```
In mm/vmalloc.c (ffffffff81255be9)
Location: include/linux/vmalloc.h:116
Inline: True
Inline callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:map_vm_area
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
In arch/x86/mm/ioremap.c (ffffffff81080a52)
Location: include/linux/vmalloc.h:127
Inline: True
```
```
In mm/vmalloc.c (ffffffff81267f49)
Location: include/linux/vmalloc.h:127
Inline: True
Inline callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:map_vm_area
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
In arch/x86/mm/ioremap.c (ffffffff81081b12)
Location: include/linux/vmalloc.h:136
Inline: True
```
```
In mm/vmalloc.c (ffffffff8127688d)
Location: include/linux/vmalloc.h:136
Inline: True
Inline callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:map_vm_area
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
In arch/x86/mm/ioremap.c (ffffffff81088a88)
Location: include/linux/vmalloc.h:153
Inline: True
```
```
In mm/vmalloc.c (ffffffff812a8493)
Location: include/linux/vmalloc.h:153
Inline: True
Inline callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:__vmalloc_area_node
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
In arch/x86/mm/ioremap.c (ffffffff81088cc8)
Location: include/linux/vmalloc.h:148
Inline: True
```
```
In mm/vmalloc.c (ffffffff812b36f7)
Location: include/linux/vmalloc.h:148
Inline: True
Inline callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:__vmalloc_area_node
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
In arch/x86/mm/ioremap.c (ffffffff81089996)
Location: include/linux/vmalloc.h:175
Inline: True
```
```
In mm/vmalloc.c (ffffffff812bdaf7)
Location: include/linux/vmalloc.h:175
Inline: True
Inline callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:vread
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
In arch/x86/mm/ioremap.c (ffffffff81098e36)
Location: include/linux/vmalloc.h:197
Inline: True
```
```
In mm/vmalloc.c (ffffffff813002c7)
Location: include/linux/vmalloc.h:197
Inline: True
Inline callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:vread
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
In arch/x86/mm/ioremap.c (ffffffff810abc65)
Location: include/linux/vmalloc.h:198
Inline: True
```
```
In mm/vmalloc.c (ffffffff81367626)
Location: include/linux/vmalloc.h:198
Inline: True
Inline callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:__vmalloc_area_node
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
In arch/x86/mm/ioremap.c (ffffffff810c56c9)
Location: include/linux/vmalloc.h:198
Inline: True
```
```
In mm/vmalloc.c (ffffffff813e3576)
Location: include/linux/vmalloc.h:198
Inline: True
Inline callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:__vmalloc_area_node
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
In arch/x86/mm/ioremap.c (ffffffff810c8e59)
Location: include/linux/vmalloc.h:196
Inline: True
```
```
In mm/vmalloc.c (ffffffff8141827d)
Location: include/linux/vmalloc.h:196
Inline: True
Inline callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vread_iter
  - mm/vmalloc.c:__vmalloc_area_node
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
In arch/x86/mm/ioremap.c (ffffffff810d1559)
Location: include/linux/vmalloc.h:196
Inline: True
```
```
In mm/vmalloc.c (ffffffff81444dcd)
Location: include/linux/vmalloc.h:196
Inline: True
Inline callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vread_iter
  - mm/vmalloc.c:__vmalloc_area_node
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffff80001030cd3c)
Location: include/linux/vmalloc.h:136
Inline: True
Inline callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:map_vm_area
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c052940c)
Location: include/linux/vmalloc.h:136
Inline: True
Inline callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:map_vm_area
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0000000003dd54c)
Location: include/linux/vmalloc.h:136
Inline: True
Inline callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:map_vm_area
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffe000215d4a)
Location: include/linux/vmalloc.h:136
Inline: True
Inline callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:map_vm_area
```
</details>
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
In arch/x86/mm/ioremap.c (ffffffff81080b12)
Location: include/linux/vmalloc.h:136
Inline: True
```
```
In mm/vmalloc.c (ffffffff8126eedd)
Location: include/linux/vmalloc.h:136
Inline: True
Inline callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:map_vm_area
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
In arch/x86/mm/ioremap.c (ffffffff8106fa62)
Location: include/linux/vmalloc.h:136
Inline: True
```
```
In mm/vmalloc.c (ffffffff81260e4d)
Location: include/linux/vmalloc.h:136
Inline: True
Inline callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:map_vm_area
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81080ac2)
Location: include/linux/vmalloc.h:136
Inline: True
```
```
In mm/vmalloc.c (ffffffff8126cc7d)
Location: include/linux/vmalloc.h:136
Inline: True
Inline callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:map_vm_area
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
In arch/x86/mm/ioremap.c (ffffffff81082be2)
Location: include/linux/vmalloc.h:136
Inline: True
```
```
In mm/vmalloc.c (ffffffff8127b89d)
Location: include/linux/vmalloc.h:136
Inline: True
Inline callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:map_vm_area
```
</details>
</li>
</ul>

## Differences
