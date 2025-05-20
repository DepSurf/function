# Function: <code>idt_init_desc</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff8102df7e)
Location: arch/x86/kernel/idt.c:204
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:idt_setup_from_table
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
In arch/x86/kernel/idt.c (ffffffff8102effe)
Location: arch/x86/kernel/idt.c:205
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:idt_setup_from_table
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
In arch/x86/kernel/idt.c (ffffffff8103028e)
Location: arch/x86/kernel/idt.c:205
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:idt_setup_from_table
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
In arch/x86/kernel/idt.c (ffffffff8103206d)
Location: arch/x86/kernel/idt.c:203
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:idt_setup_from_table
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
In arch/x86/kernel/idt.c (ffffffff8103292d)
Location: arch/x86/kernel/idt.c:203
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:idt_setup_from_table
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
In arch/x86/kernel/idt.c (ffffffff82cceec5)
Location: arch/x86/kernel/idt.c:181
Inline: True
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
In arch/x86/kernel/head64.c (ffffffff81003039)
Location: arch/x86/include/asm/desc.h:399
Inline: True
```
```
In arch/x86/kernel/idt.c (ffffffff82fbad8b)
Location: arch/x86/include/asm/desc.h:399
Inline: True
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
In arch/x86/kernel/head64.c (ffffffff81003039)
Location: arch/x86/include/asm/desc.h:399
Inline: True
```
```
In arch/x86/kernel/idt.c (ffffffff831c5625)
Location: arch/x86/include/asm/desc.h:399
Inline: True
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
In arch/x86/kernel/head64.c (ffffffff810030b0)
Location: arch/x86/include/asm/desc.h:420
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:early_setup_idt
```
```
In arch/x86/kernel/idt.c (ffffffff832a6382)
Location: arch/x86/include/asm/desc.h:420
Inline: True
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
In arch/x86/kernel/head64.c (ffffffff81000aef)
Location: arch/x86/include/asm/desc.h:420
Inline: True
```
```
In arch/x86/kernel/idt.c (ffffffff8345553d)
Location: arch/x86/include/asm/desc.h:420
Inline: True
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
In arch/x86/kernel/head64.c (ffffffff81000b3f)
Location: arch/x86/include/asm/desc.h:420
Inline: True
```
```
In arch/x86/kernel/idt.c (ffffffff83e733b0)
Location: arch/x86/include/asm/desc.h:420
Inline: True
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
In arch/x86/kernel/head64.c (ffffffff8104a01c)
Location: arch/x86/include/asm/desc.h:420
Inline: True
```
```
In arch/x86/kernel/idt.c (ffffffff83694e70)
Location: arch/x86/include/asm/desc.h:420
Inline: True
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
In arch/x86/kernel/head64.c (ffffffff8105127c)
Location: arch/x86/include/asm/desc.h:420
Inline: True
```
```
In arch/x86/kernel/idt.c (ffffffff838c4d60)
Location: arch/x86/include/asm/desc.h:420
Inline: True
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
In arch/x86/kernel/idt.c (ffffffff81032a8d)
Location: arch/x86/kernel/idt.c:203
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:idt_setup_from_table
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
In arch/x86/kernel/idt.c (ffffffff810223eb)
Location: arch/x86/kernel/idt.c:203
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:idt_setup_from_table
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
In arch/x86/kernel/idt.c (ffffffff810328ed)
Location: arch/x86/kernel/idt.c:203
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:idt_setup_from_table
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
In arch/x86/kernel/idt.c (ffffffff8103384d)
Location: arch/x86/kernel/idt.c:203
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:idt_setup_from_table
```
</details>
</li>
</ul>

## Differences
