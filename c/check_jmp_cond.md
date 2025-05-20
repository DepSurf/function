# Function: <code>check_jmp_cond</code>

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
In arch/x86/kernel/uprobes.c (ffffffff810657b3)
Location: arch/x86/kernel/uprobes.c:621
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:branch_emulate_op
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
In arch/x86/kernel/uprobes.c (ffffffff81065566)
Location: arch/x86/kernel/uprobes.c:621
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:branch_emulate_op
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
In arch/x86/kernel/uprobes.c (ffffffff81068a96)
Location: arch/x86/kernel/uprobes.c:621
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:branch_emulate_op
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
In arch/x86/kernel/uprobes.c (ffffffff81067d5f)
Location: arch/x86/kernel/uprobes.c:621
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:branch_emulate_op
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
In arch/x86/kernel/uprobes.c (ffffffff8106bfff)
Location: arch/x86/kernel/uprobes.c:624
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:branch_emulate_op
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
In arch/x86/kernel/uprobes.c (ffffffff8106ee09)
Location: arch/x86/kernel/uprobes.c:628
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:branch_emulate_op
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
In arch/x86/kernel/uprobes.c (ffffffff81074e1a)
Location: arch/x86/kernel/uprobes.c:628
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:branch_emulate_op
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
In arch/x86/kernel/uprobes.c (ffffffff810789fb)
Location: arch/x86/kernel/uprobes.c:618
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:branch_emulate_op
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
In arch/x86/kernel/uprobes.c (ffffffff81079a4b)
Location: arch/x86/kernel/uprobes.c:618
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:branch_emulate_op
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff81080db0)
Location: arch/x86/kernel/uprobes.c:618
Inline: True
Direct callers:
  - arch/x86/kernel/uprobes.c:branch_emulate_op
```
**Symbols:**

```
ffffffff81080db0-ffffffff81080f27: check_jmp_cond.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff81080860)
Location: arch/x86/kernel/uprobes.c:619
Inline: True
Direct callers:
  - arch/x86/kernel/uprobes.c:branch_emulate_op
```
**Symbols:**

```
ffffffff81080860-ffffffff810809d7: check_jmp_cond.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff810815e0)
Location: arch/x86/kernel/uprobes.c:619
Inline: True
Direct callers:
  - arch/x86/kernel/uprobes.c:branch_emulate_op
```
**Symbols:**

```
ffffffff810815e0-ffffffff81081755: check_jmp_cond.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff81090600)
Location: arch/x86/kernel/uprobes.c:619
Inline: True
Direct callers:
  - arch/x86/kernel/uprobes.c:branch_emulate_op
```
**Symbols:**

```
ffffffff81090600-ffffffff81090775: check_jmp_cond.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff810a15d0)
Location: arch/x86/kernel/uprobes.c:619
Inline: True
Direct callers:
  - arch/x86/kernel/uprobes.c:branch_emulate_op
```
**Symbols:**

```
ffffffff810a15d0-ffffffff810a17b7: check_jmp_cond.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff810b9750)
Location: arch/x86/kernel/uprobes.c:619
Inline: True
Direct callers:
  - arch/x86/kernel/uprobes.c:branch_emulate_op
```
**Symbols:**

```
ffffffff810b9750-ffffffff810b9937: check_jmp_cond.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff810bc920)
Location: arch/x86/kernel/uprobes.c:619
Inline: True
Direct callers:
  - arch/x86/kernel/uprobes.c:branch_emulate_op
```
**Symbols:**

```
ffffffff810bc920-ffffffff810bcaf3: check_jmp_cond.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff810c3aa0)
Location: arch/x86/kernel/uprobes.c:619
Inline: True
Direct callers:
  - arch/x86/kernel/uprobes.c:branch_emulate_op
```
**Symbols:**

```
ffffffff810c3aa0-ffffffff810c3c73: check_jmp_cond.isra.0 (STB_LOCAL)
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
In arch/x86/kernel/uprobes.c (ffffffff81078a4b)
Location: arch/x86/kernel/uprobes.c:618
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:branch_emulate_op
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
In arch/x86/kernel/uprobes.c (ffffffff8106820b)
Location: arch/x86/kernel/uprobes.c:618
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:branch_emulate_op
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
In arch/x86/kernel/uprobes.c (ffffffff810789fb)
Location: arch/x86/kernel/uprobes.c:618
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:branch_emulate_op
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
In arch/x86/kernel/uprobes.c (ffffffff8107aafb)
Location: arch/x86/kernel/uprobes.c:618
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:branch_emulate_op
```
</details>
</li>
</ul>

## Differences
