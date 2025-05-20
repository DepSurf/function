# Function: <code>pgd_large</code>

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
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/include/asm/pgtable_64.h:130
Inline: True
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
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/include/asm/pgtable_64.h:129
Inline: True
```
</details>
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
In arch/x86/mm/pti.c (0)
Location: arch/x86/include/asm/pgtable_64.h:261
Inline: True
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
In arch/x86/mm/pti.c (0)
Location: arch/x86/include/asm/pgtable_64.h:259
Inline: True
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
In arch/x86/mm/pti.c (0)
Location: arch/x86/include/asm/pgtable.h:1216
Inline: True
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
In arch/x86/mm/pti.c (0)
Location: arch/x86/include/asm/pgtable.h:1236
Inline: True
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
In arch/x86/mm/pti.c (0)
Location: arch/x86/include/asm/pgtable.h:1236
Inline: True
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
In arch/x86/mm/pti.c (0)
Location: arch/x86/include/asm/pgtable.h:1197
Inline: True
```
```
In mm/ptdump.c (0)
Location: arch/x86/include/asm/pgtable.h:1197
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
In arch/x86/mm/pti.c (0)
Location: arch/x86/include/asm/pgtable.h:1193
Inline: True
```
```
In kernel/events/core.c (0)
Location: arch/x86/include/asm/pgtable.h:1193
Inline: True
```
```
In mm/ptdump.c (0)
Location: arch/x86/include/asm/pgtable.h:1193
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
In arch/x86/mm/pti.c (0)
Location: arch/x86/include/asm/pgtable.h:1193
Inline: True
```
```
In kernel/events/core.c (0)
Location: arch/x86/include/asm/pgtable.h:1193
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1193
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/pgtable.h:1193
Inline: True
```
```
In mm/ptdump.c (0)
Location: arch/x86/include/asm/pgtable.h:1193
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
In arch/x86/mm/pti.c (0)
Location: arch/x86/include/asm/pgtable.h:1164
Inline: True
```
```
In kernel/events/core.c (0)
Location: arch/x86/include/asm/pgtable.h:1164
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1164
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/pgtable.h:1164
Inline: True
```
```
In mm/ptdump.c (0)
Location: arch/x86/include/asm/pgtable.h:1164
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
In arch/x86/mm/pti.c (0)
Location: arch/x86/include/asm/pgtable.h:1181
Inline: True
```
```
In kernel/events/core.c (0)
Location: arch/x86/include/asm/pgtable.h:1181
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1181
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/pgtable.h:1181
Inline: True
```
```
In mm/ptdump.c (0)
Location: arch/x86/include/asm/pgtable.h:1181
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
In arch/x86/mm/pti.c (0)
Location: arch/x86/include/asm/pgtable.h:1199
Inline: True
```
```
In kernel/events/core.c (0)
Location: arch/x86/include/asm/pgtable.h:1199
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1199
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/pgtable.h:1199
Inline: True
```
```
In mm/ptdump.c (0)
Location: arch/x86/include/asm/pgtable.h:1199
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
In arch/x86/mm/pti.c (0)
Location: arch/x86/include/asm/pgtable.h:1200
Inline: True
```
```
In kernel/events/core.c (0)
Location: arch/x86/include/asm/pgtable.h:1200
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1200
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/pgtable.h:1200
Inline: True
```
```
In mm/ptdump.c (0)
Location: arch/x86/include/asm/pgtable.h:1200
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
In arch/x86/mm/pti.c (0)
Location: arch/x86/include/asm/pgtable.h:1423
Inline: True
```
```
In kernel/events/core.c (0)
Location: arch/x86/include/asm/pgtable.h:1423
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1423
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/pgtable.h:1423
Inline: True
```
```
In mm/ptdump.c (0)
Location: arch/x86/include/asm/pgtable.h:1423
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
In arch/x86/mm/pti.c (0)
Location: arch/x86/include/asm/pgtable.h:1236
Inline: True
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
In arch/x86/mm/pti.c (0)
Location: arch/x86/include/asm/pgtable.h:1236
Inline: True
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
In arch/x86/mm/pti.c (0)
Location: arch/x86/include/asm/pgtable.h:1236
Inline: True
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
In arch/x86/mm/pti.c (0)
Location: arch/x86/include/asm/pgtable.h:1236
Inline: True
```
</details>
</li>
</ul>

## Differences
