# Function: <code>insn_complete</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff8106597e)
Location: arch/x86/include/asm/insn.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff810656ee)
Location: arch/x86/include/asm/insn.h:145
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
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
In arch/x86/kernel/uprobes.c (ffffffff81068c1e)
Location: arch/x86/include/asm/insn.h:145
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
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
In arch/x86/kernel/uprobes.c (ffffffff81067efe)
Location: arch/x86/include/asm/insn.h:145
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
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
In arch/x86/kernel/uprobes.c (ffffffff8106c1a8)
Location: arch/x86/include/asm/insn.h:145
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
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
In arch/x86/kernel/uprobes.c (ffffffff8106efa8)
Location: arch/x86/include/asm/insn.h:145
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
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
In arch/x86/kernel/uprobes.c (ffffffff81075018)
Location: arch/x86/include/asm/insn.h:145
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
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
In arch/x86/kernel/uprobes.c (ffffffff81078c16)
Location: arch/x86/include/asm/insn.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
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
In arch/x86/kernel/uprobes.c (ffffffff81079c66)
Location: arch/x86/include/asm/insn.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
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
In arch/x86/kernel/alternative.c (ffffffff8103c99f)
Location: arch/x86/include/asm/insn.h:138
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_loc_init
```
```
In arch/x86/kernel/uprobes.c (ffffffff810810cf)
Location: arch/x86/include/asm/insn.h:138
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:uprobe_init_insn
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
In arch/x86/kernel/alternative.c (ffffffff8103ce3f)
Location: arch/x86/include/asm/insn.h:138
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_loc_init
```
```
In arch/x86/kernel/uprobes.c (ffffffff81080b81)
Location: arch/x86/include/asm/insn.h:138
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:uprobe_init_insn
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
In arch/x86/lib/insn.c (ffffffff81607c66)
Location: arch/x86/lib/insn.c:718
Inline: True
Inline callers:
  - arch/x86/lib/insn.c:insn_decode
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
In arch/x86/lib/insn.c (ffffffff816768a6)
Location: arch/x86/lib/insn.c:719
Inline: True
Inline callers:
  - arch/x86/lib/insn.c:insn_decode
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
In arch/x86/lib/insn.c (ffffffff817917b7)
Location: arch/x86/lib/insn.c:719
Inline: True
Inline callers:
  - arch/x86/lib/insn.c:insn_decode
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
In arch/x86/lib/insn.c (ffffffff8204f487)
Location: arch/x86/lib/insn.c:719
Inline: True
Inline callers:
  - arch/x86/lib/insn.c:insn_decode
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
In arch/x86/lib/insn.c (ffffffff820cdd07)
Location: arch/x86/lib/insn.c:719
Inline: True
Inline callers:
  - arch/x86/lib/insn.c:insn_decode
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
In arch/x86/lib/insn.c (ffffffff821a8527)
Location: arch/x86/lib/insn.c:719
Inline: True
Inline callers:
  - arch/x86/lib/insn.c:insn_decode
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
In arch/x86/kernel/uprobes.c (ffffffff81078c66)
Location: arch/x86/include/asm/insn.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
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
In arch/x86/kernel/uprobes.c (ffffffff81068416)
Location: arch/x86/include/asm/insn.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
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
In arch/x86/kernel/uprobes.c (ffffffff81078c16)
Location: arch/x86/include/asm/insn.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
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
In arch/x86/kernel/uprobes.c (ffffffff8107ad16)
Location: arch/x86/include/asm/insn.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
```
</details>
</li>
</ul>

## Differences
