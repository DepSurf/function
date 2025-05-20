# Function: <code>IO_APIC_get_PCI_irq_vector</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int IO_APIC_get_PCI_irq_vector(int bus, int slot, int pin);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81057810)
Location: arch/x86/kernel/apic/io_apic.c:1142
Inline: True
Direct callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pirq_enable_irq
```
**Symbols:**

```
ffffffff81057810-ffffffff810579eb: IO_APIC_get_PCI_irq_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int IO_APIC_get_PCI_irq_vector(int bus, int slot, int pin);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81057ad0)
Location: arch/x86/kernel/apic/io_apic.c:1143
Inline: True
Direct callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pirq_enable_irq
```
**Symbols:**

```
ffffffff81057ad0-ffffffff81057cd4: IO_APIC_get_PCI_irq_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int IO_APIC_get_PCI_irq_vector(int bus, int slot, int pin);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105a860)
Location: arch/x86/kernel/apic/io_apic.c:1142
Inline: True
Direct callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pirq_enable_irq
```
**Symbols:**

```
ffffffff8105a860-ffffffff8105aa64: IO_APIC_get_PCI_irq_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int IO_APIC_get_PCI_irq_vector(int bus, int slot, int pin);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81059e70)
Location: arch/x86/kernel/apic/io_apic.c:1142
Inline: True
Direct callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pirq_enable_irq
```
**Symbols:**

```
ffffffff81059e70-ffffffff8105a060: IO_APIC_get_PCI_irq_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int IO_APIC_get_PCI_irq_vector(int bus, int slot, int pin);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105e360)
Location: arch/x86/kernel/apic/io_apic.c:1144
Inline: True
Direct callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pirq_enable_irq
```
**Symbols:**

```
ffffffff8105e360-ffffffff8105e550: IO_APIC_get_PCI_irq_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int IO_APIC_get_PCI_irq_vector(int bus, int slot, int pin);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:1145
Inline: True
Direct callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pirq_enable_irq
```
**Symbols:**

```
ffffffff81062156-ffffffff8106218c: IO_APIC_get_PCI_irq_vector.cold.25 (STB_LOCAL)
ffffffff81061360-ffffffff81061513: IO_APIC_get_PCI_irq_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int IO_APIC_get_PCI_irq_vector(int bus, int slot, int pin);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:1145
Inline: True
Direct callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pirq_enable_irq
```
**Symbols:**

```
ffffffff81067e4b-ffffffff81067e81: IO_APIC_get_PCI_irq_vector.cold.23 (STB_LOCAL)
ffffffff81067040-ffffffff810671f3: IO_APIC_get_PCI_irq_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int IO_APIC_get_PCI_irq_vector(int bus, int slot, int pin);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:1148
Inline: True
Direct callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pirq_enable_irq
```
**Symbols:**

```
ffffffff8106b608-ffffffff8106b63e: IO_APIC_get_PCI_irq_vector.cold (STB_LOCAL)
ffffffff8106a810-ffffffff8106a99f: IO_APIC_get_PCI_irq_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int IO_APIC_get_PCI_irq_vector(int bus, int slot, int pin);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:1148
Inline: True
Direct callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pirq_enable_irq
```
**Symbols:**

```
ffffffff8106bf6c-ffffffff8106bfa2: IO_APIC_get_PCI_irq_vector.cold (STB_LOCAL)
ffffffff8106b1b0-ffffffff8106b33f: IO_APIC_get_PCI_irq_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int IO_APIC_get_PCI_irq_vector(int bus, int slot, int pin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:1135
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pirq_enable_irq
```
**Symbols:**

```
ffffffff810732a2-ffffffff810732d1: IO_APIC_get_PCI_irq_vector.cold (STB_LOCAL)
ffffffff810725a0-ffffffff81072772: IO_APIC_get_PCI_irq_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int IO_APIC_get_PCI_irq_vector(int bus, int slot, int pin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:1144
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pirq_enable_irq
```
**Symbols:**

```
ffffffff81bd73ea-ffffffff81bd7419: IO_APIC_get_PCI_irq_vector.cold (STB_LOCAL)
ffffffff81073aa0-ffffffff81073c72: IO_APIC_get_PCI_irq_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int IO_APIC_get_PCI_irq_vector(int bus, int slot, int pin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:1144
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pirq_enable_irq
```
**Symbols:**

```
ffffffff81bc9585-ffffffff81bc95b4: IO_APIC_get_PCI_irq_vector.cold (STB_LOCAL)
ffffffff81074520-ffffffff810746f2: IO_APIC_get_PCI_irq_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int IO_APIC_get_PCI_irq_vector(int bus, int slot, int pin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:1144
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pirq_enable_irq
```
**Symbols:**

```
ffffffff81c9e082-ffffffff81c9e0b1: IO_APIC_get_PCI_irq_vector.cold (STB_LOCAL)
ffffffff81080440-ffffffff810808f3: IO_APIC_get_PCI_irq_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int IO_APIC_get_PCI_irq_vector(int bus, int slot, int pin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:1145
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pirq_enable_irq
```
**Symbols:**

```
ffffffff81e4d5ee-ffffffff81e4d61a: IO_APIC_get_PCI_irq_vector.cold (STB_LOCAL)
ffffffff81090120-ffffffff8109060e: IO_APIC_get_PCI_irq_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int IO_APIC_get_PCI_irq_vector(int bus, int slot, int pin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a4820)
Location: arch/x86/kernel/apic/io_apic.c:1145
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pirq_enable_irq
```
**Symbols:**

```
ffffffff810a4820-ffffffff810a4d27: IO_APIC_get_PCI_irq_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int IO_APIC_get_PCI_irq_vector(int bus, int slot, int pin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a7900)
Location: arch/x86/kernel/apic/io_apic.c:1146
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pirq_enable_irq
```
**Symbols:**

```
ffffffff810a7900-ffffffff810a7e10: IO_APIC_get_PCI_irq_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int IO_APIC_get_PCI_irq_vector(int bus, int slot, int pin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810ae960)
Location: arch/x86/kernel/apic/io_apic.c:1146
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pirq_enable_irq
```
**Symbols:**

```
ffffffff810ae960-ffffffff810aee70: IO_APIC_get_PCI_irq_vector (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int IO_APIC_get_PCI_irq_vector(int bus, int slot, int pin);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:1148
Inline: True
Direct callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pirq_enable_irq
```
**Symbols:**

```
ffffffff8106ba5c-ffffffff8106ba92: IO_APIC_get_PCI_irq_vector.cold (STB_LOCAL)
ffffffff8106aca0-ffffffff8106ae2f: IO_APIC_get_PCI_irq_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int IO_APIC_get_PCI_irq_vector(int bus, int slot, int pin);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:1148
Inline: True
Direct callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pirq_enable_irq
```
**Symbols:**

```
ffffffff8105bd8c-ffffffff8105bdc2: IO_APIC_get_PCI_irq_vector.cold (STB_LOCAL)
ffffffff8105b000-ffffffff8105b18f: IO_APIC_get_PCI_irq_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int IO_APIC_get_PCI_irq_vector(int bus, int slot, int pin);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:1148
Inline: True
Direct callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pirq_enable_irq
```
**Symbols:**

```
ffffffff8106bf0c-ffffffff8106bf42: IO_APIC_get_PCI_irq_vector.cold (STB_LOCAL)
ffffffff8106b150-ffffffff8106b2df: IO_APIC_get_PCI_irq_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int IO_APIC_get_PCI_irq_vector(int bus, int slot, int pin);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:1148
Inline: True
Direct callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pirq_enable_irq
```
**Symbols:**

```
ffffffff8106d60c-ffffffff8106d642: IO_APIC_get_PCI_irq_vector.cold (STB_LOCAL)
ffffffff8106c850-ffffffff8106c9df: IO_APIC_get_PCI_irq_vector (STB_GLOBAL)
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
