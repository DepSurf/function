# Function: <code>pirq_check_routing_table</code>

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
In arch/x86/pci/irq.c (ffffffff816fae80)
Location: arch/x86/pci/irq.c:64
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
  - arch/x86/pci/irq.c:pcibios_irq_init
Direct callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff816fae80-ffffffff816faeb3: pirq_check_routing_table.part.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff81fe767e)
Location: arch/x86/pci/irq.c:64
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
  - arch/x86/pci/irq.c:pcibios_irq_init
Direct callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff8175fcdf-ffffffff8175fd12: pirq_check_routing_table.part.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff82025eb9)
Location: arch/x86/pci/irq.c:64
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
  - arch/x86/pci/irq.c:pcibios_irq_init
Direct callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff8178c1e5-ffffffff8178c218: pirq_check_routing_table.part.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct irq_routing_table *pirq_check_routing_table(u8 *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff817aa413)
Location: arch/x86/pci/irq.c:64
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff817aa413-ffffffff817aa45c: pirq_check_routing_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct irq_routing_table *pirq_check_routing_table(u8 *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff818218e3)
Location: arch/x86/pci/irq.c:65
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff818218e3-ffffffff8182192c: pirq_check_routing_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct irq_routing_table *pirq_check_routing_table(u8 *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff8186bb33)
Location: arch/x86/pci/irq.c:65
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff8186bb33-ffffffff8186bb76: pirq_check_routing_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct irq_routing_table *pirq_check_routing_table(u8 *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff8188bc13)
Location: arch/x86/pci/irq.c:65
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff8188bc13-ffffffff8188bc56: pirq_check_routing_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct irq_routing_table *pirq_check_routing_table(u8 *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff818d6373)
Location: arch/x86/pci/irq.c:65
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff818d6373-ffffffff818d63b6: pirq_check_routing_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct irq_routing_table *pirq_check_routing_table(u8 *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff819086f3)
Location: arch/x86/pci/irq.c:65
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff819086f3-ffffffff81908736: pirq_check_routing_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct irq_routing_table *pirq_check_routing_table(u8 *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff81bb8ff3)
Location: arch/x86/pci/irq.c:65
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff81bb8ff3-ffffffff81bb9036: pirq_check_routing_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct irq_routing_table *pirq_check_routing_table(u8 *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff81c34712)
Location: arch/x86/pci/irq.c:65
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff81c34712-ffffffff81c34755: pirq_check_routing_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct irq_routing_table *pirq_check_routing_table(u8 *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff81c26aee)
Location: arch/x86/pci/irq.c:65
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff81c26aee-ffffffff81c26b2e: pirq_check_routing_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct irq_routing_table *pirq_check_routing_table(u8 *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff81d4498b)
Location: arch/x86/pci/irq.c:71
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff81d4498b-ffffffff81d449cb: pirq_check_routing_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct irq_routing_table *pirq_check_routing_table(u8 *addr, u8 *limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff81f1189a)
Location: arch/x86/pci/irq.c:73
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pirq_find_routing_table
  - arch/x86/pci/irq.c:pirq_find_routing_table
```
**Symbols:**

```
ffffffff81f1189a-ffffffff81f11902: pirq_check_routing_table (STB_LOCAL)
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
In arch/x86/pci/irq.c (ffffffff83f161b1)
Location: arch/x86/pci/irq.c:73
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_find_routing_table
  - arch/x86/pci/irq.c:pirq_find_routing_table
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
In arch/x86/pci/irq.c (ffffffff8373c8f1)
Location: arch/x86/pci/irq.c:73
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_find_routing_table
  - arch/x86/pci/irq.c:pirq_find_routing_table
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
In arch/x86/pci/irq.c (ffffffff8397128f)
Location: arch/x86/pci/irq.c:73
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pirq_find_routing_table
  - arch/x86/pci/irq.c:pirq_find_routing_table
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
<summary>In <code>aws</code>: ✅</summary>

```c
struct irq_routing_table *pirq_check_routing_table(u8 *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff818a7ab3)
Location: arch/x86/pci/irq.c:65
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff818a7ab3-ffffffff818a7af6: pirq_check_routing_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct irq_routing_table *pirq_check_routing_table(u8 *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff818625d3)
Location: arch/x86/pci/irq.c:65
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff818625d3-ffffffff81862616: pirq_check_routing_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct irq_routing_table *pirq_check_routing_table(u8 *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff818f9113)
Location: arch/x86/pci/irq.c:65
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff818f9113-ffffffff818f9156: pirq_check_routing_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct irq_routing_table *pirq_check_routing_table(u8 *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff8191a213)
Location: arch/x86/pci/irq.c:65
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff8191a213-ffffffff8191a256: pirq_check_routing_table (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 *limit</code>
</li>
</ul>
</details>
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
