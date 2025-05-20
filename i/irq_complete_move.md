# Function: <code>irq_complete_move</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void irq_complete_move(struct irq_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81055b00)
Location: arch/x86/kernel/apic/vector.c:652
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
**Symbols:**

```
ffffffff81055b00-ffffffff81055b25: irq_complete_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void irq_complete_move(struct irq_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81055757)
Location: arch/x86/kernel/apic/vector.c:654
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
**Symbols:**

```
ffffffff81055d70-ffffffff81055d8e: irq_complete_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void irq_complete_move(struct irq_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810586d7)
Location: arch/x86/kernel/apic/vector.c:654
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
**Symbols:**

```
ffffffff81058b10-ffffffff81058b2e: irq_complete_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void irq_complete_move(struct irq_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810576bf)
Location: arch/x86/kernel/apic/vector.c:675
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
**Symbols:**

```
ffffffff81058170-ffffffff8105818e: irq_complete_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void irq_complete_move(struct irq_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8105ba7f)
Location: arch/x86/kernel/apic/vector.c:912
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
**Symbols:**

```
ffffffff8105c670-ffffffff8105c68e: irq_complete_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void irq_complete_move(struct irq_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8105f68a)
Location: arch/x86/kernel/apic/vector.c:928
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
**Symbols:**

```
ffffffff8105f6d0-ffffffff8105f6ee: irq_complete_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void irq_complete_move(struct irq_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810652fa)
Location: arch/x86/kernel/apic/vector.c:919
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
**Symbols:**

```
ffffffff81065340-ffffffff8106535e: irq_complete_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void irq_complete_move(struct irq_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810689db)
Location: arch/x86/kernel/apic/vector.c:916
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
**Symbols:**

```
ffffffff81068a20-ffffffff81068a3e: irq_complete_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void irq_complete_move(struct irq_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8106934b)
Location: arch/x86/kernel/apic/vector.c:927
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
**Symbols:**

```
ffffffff81069390-ffffffff810693ae: irq_complete_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void irq_complete_move(struct irq_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8106ec36)
Location: arch/x86/kernel/apic/vector.c:914
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
**Symbols:**

```
ffffffff81070350-ffffffff81070373: irq_complete_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void irq_complete_move(struct irq_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81070246)
Location: arch/x86/kernel/apic/vector.c:966
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
**Symbols:**

```
ffffffff810718b0-ffffffff810718d3: irq_complete_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void irq_complete_move(struct irq_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81071f26)
Location: arch/x86/kernel/apic/vector.c:999
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
**Symbols:**

```
ffffffff810723b0-ffffffff810723d3: irq_complete_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void irq_complete_move(struct irq_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8107dd46)
Location: arch/x86/kernel/apic/vector.c:999
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
**Symbols:**

```
ffffffff8107e290-ffffffff8107e2b3: irq_complete_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void irq_complete_move(struct irq_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8108be35)
Location: arch/x86/kernel/apic/vector.c:999
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
**Symbols:**

```
ffffffff8108d920-ffffffff8108d953: irq_complete_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void irq_complete_move(struct irq_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810a0335)
Location: arch/x86/kernel/apic/vector.c:995
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
**Symbols:**

```
ffffffff810a2050-ffffffff810a2083: irq_complete_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void irq_complete_move(struct irq_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810a32b5)
Location: arch/x86/kernel/apic/vector.c:995
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
**Symbols:**

```
ffffffff810a5030-ffffffff810a5063: irq_complete_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void irq_complete_move(struct irq_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810aa1f5)
Location: arch/x86/kernel/apic/vector.c:1053
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
**Symbols:**

```
ffffffff810ac0c0-ffffffff810ac0f3: irq_complete_move (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void irq_complete_move(struct irq_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81068e3b)
Location: arch/x86/kernel/apic/vector.c:927
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
**Symbols:**

```
ffffffff81068e80-ffffffff81068e9e: irq_complete_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void irq_complete_move(struct irq_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810591ab)
Location: arch/x86/kernel/apic/vector.c:927
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
**Symbols:**

```
ffffffff810591f0-ffffffff8105920e: irq_complete_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void irq_complete_move(struct irq_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810692eb)
Location: arch/x86/kernel/apic/vector.c:927
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
**Symbols:**

```
ffffffff81069330-ffffffff8106934e: irq_complete_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void irq_complete_move(struct irq_cfg *cfg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8106a9eb)
Location: arch/x86/kernel/apic/vector.c:927
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
```
**Symbols:**

```
ffffffff8106aa30-ffffffff8106aa4e: irq_complete_move (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
