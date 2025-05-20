# Function: <code>__irq_complete_move</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810554c0)
Location: arch/x86/kernel/apic/vector.c:638
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:irq_complete_move
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
Direct callers:
  - arch/x86/kernel/apic/vector.c:irq_complete_move
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
```
**Symbols:**

```
ffffffff810554c0-ffffffff810554ed: __irq_complete_move.part.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __irq_complete_move(struct irq_cfg *cfg, unsigned int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81055270)
Location: arch/x86/kernel/apic/vector.c:640
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
```
**Symbols:**

```
ffffffff81055270-ffffffff810552a0: __irq_complete_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __irq_complete_move(struct irq_cfg *cfg, unsigned int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81058670)
Location: arch/x86/kernel/apic/vector.c:640
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
```
**Symbols:**

```
ffffffff81058670-ffffffff810586a3: __irq_complete_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __irq_complete_move(struct irq_cfg *cfg, unsigned int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81057660)
Location: arch/x86/kernel/apic/vector.c:661
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
```
**Symbols:**

```
ffffffff81057660-ffffffff81057693: __irq_complete_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __irq_complete_move(struct irq_cfg *cfg, unsigned int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8105b190)
Location: arch/x86/kernel/apic/vector.c:900
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
```
**Symbols:**

```
ffffffff8105b190-ffffffff8105b1bb: __irq_complete_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __irq_complete_move(struct irq_cfg *cfg, unsigned int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8105ed40)
Location: arch/x86/kernel/apic/vector.c:916
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
```
**Symbols:**

```
ffffffff8105ed40-ffffffff8105ed6a: __irq_complete_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __irq_complete_move(struct irq_cfg *cfg, unsigned int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81064e00)
Location: arch/x86/kernel/apic/vector.c:907
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
```
**Symbols:**

```
ffffffff81064e00-ffffffff81064e2a: __irq_complete_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __irq_complete_move(struct irq_cfg *cfg, unsigned int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81068510)
Location: arch/x86/kernel/apic/vector.c:904
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
```
**Symbols:**

```
ffffffff81068510-ffffffff81068538: __irq_complete_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __irq_complete_move(struct irq_cfg *cfg, unsigned int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81068e50)
Location: arch/x86/kernel/apic/vector.c:915
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
```
**Symbols:**

```
ffffffff81068e50-ffffffff81068e78: __irq_complete_move (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __irq_complete_move(struct irq_cfg *cfg, unsigned int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81068940)
Location: arch/x86/kernel/apic/vector.c:915
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
```
**Symbols:**

```
ffffffff81068940-ffffffff81068968: __irq_complete_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __irq_complete_move(struct irq_cfg *cfg, unsigned int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81058cb0)
Location: arch/x86/kernel/apic/vector.c:915
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
```
**Symbols:**

```
ffffffff81058cb0-ffffffff81058cd8: __irq_complete_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __irq_complete_move(struct irq_cfg *cfg, unsigned int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81068df0)
Location: arch/x86/kernel/apic/vector.c:915
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
```
**Symbols:**

```
ffffffff81068df0-ffffffff81068e18: __irq_complete_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __irq_complete_move(struct irq_cfg *cfg, unsigned int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810693b0)
Location: arch/x86/kernel/apic/vector.c:915
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
```
**Symbols:**

```
ffffffff810693b0-ffffffff810693d8: __irq_complete_move (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
