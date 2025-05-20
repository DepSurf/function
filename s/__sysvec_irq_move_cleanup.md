# Function: <code>__sysvec_irq_move_cleanup</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __sysvec_irq_move_cleanup(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8106ef80)
Location: arch/x86/kernel/apic/vector.c:856
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:sysvec_irq_move_cleanup
```
**Symbols:**

```
ffffffff8106ef80-ffffffff8106f040: __sysvec_irq_move_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __sysvec_irq_move_cleanup(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81070510)
Location: arch/x86/kernel/apic/vector.c:908
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:sysvec_irq_move_cleanup
```
**Symbols:**

```
ffffffff81070510-ffffffff810705d0: __sysvec_irq_move_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __sysvec_irq_move_cleanup(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81071f80)
Location: arch/x86/kernel/apic/vector.c:941
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:sysvec_irq_move_cleanup
```
**Symbols:**

```
ffffffff81071f80-ffffffff81072040: __sysvec_irq_move_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __sysvec_irq_move_cleanup(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8107dda0)
Location: arch/x86/kernel/apic/vector.c:941
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:sysvec_irq_move_cleanup
```
**Symbols:**

```
ffffffff8107dda0-ffffffff8107de60: __sysvec_irq_move_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __sysvec_irq_move_cleanup(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8108bfe0)
Location: arch/x86/kernel/apic/vector.c:941
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:sysvec_irq_move_cleanup
```
**Symbols:**

```
ffffffff8108bfe0-ffffffff8108c0a0: __sysvec_irq_move_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __sysvec_irq_move_cleanup(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810a0500)
Location: arch/x86/kernel/apic/vector.c:937
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:sysvec_irq_move_cleanup
```
**Symbols:**

```
ffffffff810a0500-ffffffff810a05c0: __sysvec_irq_move_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __sysvec_irq_move_cleanup(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810a3480)
Location: arch/x86/kernel/apic/vector.c:937
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:sysvec_irq_move_cleanup
```
**Symbols:**

```
ffffffff810a3480-ffffffff810a3540: __sysvec_irq_move_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
