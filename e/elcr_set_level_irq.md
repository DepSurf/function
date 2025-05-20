# Function: <code>elcr_set_level_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void elcr_set_level_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff816f9980)
Location: arch/x86/pci/irq.c:152
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_pic
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
```
**Symbols:**

```
ffffffff816f9980-ffffffff816f99e7: elcr_set_level_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void elcr_set_level_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff8175e6a0)
Location: arch/x86/pci/irq.c:152
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_pic
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
```
**Symbols:**

```
ffffffff8175e6a0-ffffffff8175e707: elcr_set_level_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void elcr_set_level_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff8178abd0)
Location: arch/x86/pci/irq.c:152
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_pic
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
```
**Symbols:**

```
ffffffff8178abd0-ffffffff8178ac37: elcr_set_level_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void elcr_set_level_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff817a9b00)
Location: arch/x86/pci/irq.c:152
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_pic
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
```
**Symbols:**

```
ffffffff817a9b00-ffffffff817a9b68: elcr_set_level_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void elcr_set_level_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff81820fb0)
Location: arch/x86/pci/irq.c:153
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_pic
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
```
**Symbols:**

```
ffffffff81820fb0-ffffffff81821018: elcr_set_level_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void elcr_set_level_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (0)
Location: arch/x86/pci/irq.c:153
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_pic
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
```
**Symbols:**

```
ffffffff8186bb76-ffffffff8186bbc1: elcr_set_level_irq.cold.7 (STB_LOCAL)
ffffffff8186b260-ffffffff8186b289: elcr_set_level_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void elcr_set_level_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (0)
Location: arch/x86/pci/irq.c:153
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_pic
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
```
**Symbols:**

```
ffffffff8188bc56-ffffffff8188bca1: elcr_set_level_irq.cold.7 (STB_LOCAL)
ffffffff8188b330-ffffffff8188b359: elcr_set_level_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void elcr_set_level_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (0)
Location: arch/x86/pci/irq.c:153
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_pic
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
```
**Symbols:**

```
ffffffff818d6450-ffffffff818d6496: elcr_set_level_irq.cold (STB_LOCAL)
ffffffff818d5bd0-ffffffff818d5bfc: elcr_set_level_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void elcr_set_level_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (0)
Location: arch/x86/pci/irq.c:153
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_pic
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
```
**Symbols:**

```
ffffffff819087d0-ffffffff81908816: elcr_set_level_irq.cold (STB_LOCAL)
ffffffff81907f50-ffffffff81907f7c: elcr_set_level_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void elcr_set_level_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (0)
Location: arch/x86/pci/irq.c:153
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_pic
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
```
**Symbols:**

```
ffffffff81bb9130-ffffffff81bb9176: elcr_set_level_irq.cold (STB_LOCAL)
ffffffff81bb8830-ffffffff81bb885c: elcr_set_level_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void elcr_set_level_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (0)
Location: arch/x86/pci/irq.c:153
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_pic
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
```
**Symbols:**

```
ffffffff81c3484f-ffffffff81c34895: elcr_set_level_irq.cold (STB_LOCAL)
ffffffff81bcd440-ffffffff81bcd46c: elcr_set_level_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void elcr_set_level_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (0)
Location: arch/x86/pci/irq.c:153
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_pic
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
```
**Symbols:**

```
ffffffff81c26c28-ffffffff81c26c6e: elcr_set_level_irq.cold (STB_LOCAL)
ffffffff81bc0e70-ffffffff81bc0e9c: elcr_set_level_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void elcr_set_level_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (0)
Location: arch/x86/pci/irq.c:159
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_pic
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pirq_finali_lvl
```
**Symbols:**

```
ffffffff81d44ac5-ffffffff81d44b0b: elcr_set_level_irq.cold (STB_LOCAL)
ffffffff81c911f0-ffffffff81c9121c: elcr_set_level_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void elcr_set_level_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (0)
Location: arch/x86/pci/irq.c:243
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_pic
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pirq_finali_lvl
```
**Symbols:**

```
ffffffff81f11a65-ffffffff81f11aae: elcr_set_level_irq.cold (STB_LOCAL)
ffffffff81e40700-ffffffff81e40747: elcr_set_level_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void elcr_set_level_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff8201a9d0)
Location: arch/x86/pci/irq.c:243
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_pic
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pirq_finali_lvl
```
**Symbols:**

```
ffffffff8201a9d0-ffffffff8201aa64: elcr_set_level_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void elcr_set_level_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff8209b050)
Location: arch/x86/pci/irq.c:243
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_pic
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pirq_finali_lvl
```
**Symbols:**

```
ffffffff8209b050-ffffffff8209b0e4: elcr_set_level_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void elcr_set_level_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff82172790)
Location: arch/x86/pci/irq.c:243
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_pic
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pirq_finali_lvl
```
**Symbols:**

```
ffffffff82172790-ffffffff82172824: elcr_set_level_irq (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void elcr_set_level_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (0)
Location: arch/x86/pci/irq.c:153
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_pic
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
```
**Symbols:**

```
ffffffff818a7b90-ffffffff818a7bd6: elcr_set_level_irq.cold (STB_LOCAL)
ffffffff818a7310-ffffffff818a733c: elcr_set_level_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void elcr_set_level_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (0)
Location: arch/x86/pci/irq.c:153
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_pic
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
```
**Symbols:**

```
ffffffff818626b0-ffffffff818626f6: elcr_set_level_irq.cold (STB_LOCAL)
ffffffff81861e30-ffffffff81861e5c: elcr_set_level_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void elcr_set_level_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (0)
Location: arch/x86/pci/irq.c:153
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_pic
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
```
**Symbols:**

```
ffffffff818f91f0-ffffffff818f9236: elcr_set_level_irq.cold (STB_LOCAL)
ffffffff818f8970-ffffffff818f899c: elcr_set_level_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void elcr_set_level_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (0)
Location: arch/x86/pci/irq.c:153
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_pic
  - arch/x86/pci/irq.c:pcibios_lookup_irq
  - arch/x86/pci/irq.c:pcibios_lookup_irq
```
**Symbols:**

```
ffffffff8191a2f0-ffffffff8191a336: elcr_set_level_irq.cold (STB_LOCAL)
ffffffff81919a70-ffffffff81919a9c: elcr_set_level_irq (STB_GLOBAL)
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
