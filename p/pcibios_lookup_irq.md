# Function: <code>pcibios_lookup_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pcibios_lookup_irq(struct pci_dev *dev, int assign);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff816f99f0)
Location: arch/x86/pci/irq.c:879
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
```
**Symbols:**

```
ffffffff816f99f0-ffffffff816f9fcc: pcibios_lookup_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pcibios_lookup_irq(struct pci_dev *dev, int assign);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff8175e710)
Location: arch/x86/pci/irq.c:879
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
```
**Symbols:**

```
ffffffff8175e710-ffffffff8175ed06: pcibios_lookup_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pcibios_lookup_irq(struct pci_dev *dev, int assign);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff8178ac40)
Location: arch/x86/pci/irq.c:879
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
```
**Symbols:**

```
ffffffff8178ac40-ffffffff8178b236: pcibios_lookup_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pcibios_lookup_irq(struct pci_dev *dev, int assign);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff817a9b70)
Location: arch/x86/pci/irq.c:879
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
```
**Symbols:**

```
ffffffff817a9b70-ffffffff817aa18f: pcibios_lookup_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pcibios_lookup_irq(struct pci_dev *dev, int assign);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff81821020)
Location: arch/x86/pci/irq.c:880
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
```
**Symbols:**

```
ffffffff81821020-ffffffff81821655: pcibios_lookup_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pcibios_lookup_irq(struct pci_dev *dev, int assign);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff8186b290)
Location: arch/x86/pci/irq.c:881
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
```
**Symbols:**

```
ffffffff8186b290-ffffffff8186b8b8: pcibios_lookup_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pcibios_lookup_irq(struct pci_dev *dev, int assign);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff8188b360)
Location: arch/x86/pci/irq.c:881
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
```
**Symbols:**

```
ffffffff8188b360-ffffffff8188b998: pcibios_lookup_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pcibios_lookup_irq(struct pci_dev *dev, int assign);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (0)
Location: arch/x86/pci/irq.c:881
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
```
**Symbols:**

```
ffffffff818d5c00-ffffffff818d618b: pcibios_lookup_irq (STB_LOCAL)
ffffffff818d6496-ffffffff818d65d0: pcibios_lookup_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int pcibios_lookup_irq(struct pci_dev *dev, int assign);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (0)
Location: arch/x86/pci/irq.c:881
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
```
**Symbols:**

```
ffffffff81907f80-ffffffff8190850b: pcibios_lookup_irq (STB_LOCAL)
ffffffff81908816-ffffffff81908950: pcibios_lookup_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int pcibios_lookup_irq(struct pci_dev *dev, int assign);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (0)
Location: arch/x86/pci/irq.c:881
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
```
**Symbols:**

```
ffffffff81bb8860-ffffffff81bb8e02: pcibios_lookup_irq (STB_LOCAL)
ffffffff81bb9176-ffffffff81bb92b7: pcibios_lookup_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int pcibios_lookup_irq(struct pci_dev *dev, int assign);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (0)
Location: arch/x86/pci/irq.c:881
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
```
**Symbols:**

```
ffffffff81bcd470-ffffffff81bcda12: pcibios_lookup_irq (STB_LOCAL)
ffffffff81c34895-ffffffff81c349d6: pcibios_lookup_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int pcibios_lookup_irq(struct pci_dev *dev, int assign);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (0)
Location: arch/x86/pci/irq.c:881
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
```
**Symbols:**

```
ffffffff81bc0ea0-ffffffff81bc13ef: pcibios_lookup_irq (STB_LOCAL)
ffffffff81c26c6e-ffffffff81c26dbe: pcibios_lookup_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pcibios_lookup_irq(struct pci_dev *dev, int assign);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (0)
Location: arch/x86/pci/irq.c:1148
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
```
**Symbols:**

```
ffffffff81c912a0-ffffffff81c91961: pcibios_lookup_irq (STB_LOCAL)
ffffffff81d44b24-ffffffff81d44d49: pcibios_lookup_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pcibios_lookup_irq(struct pci_dev *dev, int assign);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (0)
Location: arch/x86/pci/irq.c:1394
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
```
**Symbols:**

```
ffffffff81e407d0-ffffffff81e40de1: pcibios_lookup_irq (STB_LOCAL)
ffffffff81f11aae-ffffffff81f11c98: pcibios_lookup_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int pcibios_lookup_irq(struct pci_dev *dev, int assign);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (0)
Location: arch/x86/pci/irq.c:1394
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
```
**Symbols:**

```
ffffffff8201ab10-ffffffff8201b29a: pcibios_lookup_irq (STB_LOCAL)
ffffffff820b72da-ffffffff820b735a: pcibios_lookup_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int pcibios_lookup_irq(struct pci_dev *dev, int assign);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (0)
Location: arch/x86/pci/irq.c:1394
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
```
**Symbols:**

```
ffffffff8209b190-ffffffff8209b916: pcibios_lookup_irq (STB_LOCAL)
ffffffff82138676-ffffffff821386e2: pcibios_lookup_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int pcibios_lookup_irq(struct pci_dev *dev, int assign);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (0)
Location: arch/x86/pci/irq.c:1394
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
```
**Symbols:**

```
ffffffff821728d0-ffffffff82173068: pcibios_lookup_irq (STB_LOCAL)
ffffffff8221a5d1-ffffffff8221a652: pcibios_lookup_irq.cold (STB_LOCAL)
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
int pcibios_lookup_irq(struct pci_dev *dev, int assign);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (0)
Location: arch/x86/pci/irq.c:881
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
```
**Symbols:**

```
ffffffff818a7340-ffffffff818a78cb: pcibios_lookup_irq (STB_LOCAL)
ffffffff818a7bd6-ffffffff818a7d10: pcibios_lookup_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int pcibios_lookup_irq(struct pci_dev *dev, int assign);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (0)
Location: arch/x86/pci/irq.c:881
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
```
**Symbols:**

```
ffffffff81861e60-ffffffff818623eb: pcibios_lookup_irq (STB_LOCAL)
ffffffff818626f6-ffffffff81862830: pcibios_lookup_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int pcibios_lookup_irq(struct pci_dev *dev, int assign);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (0)
Location: arch/x86/pci/irq.c:881
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
```
**Symbols:**

```
ffffffff818f89a0-ffffffff818f8f2b: pcibios_lookup_irq (STB_LOCAL)
ffffffff818f9236-ffffffff818f9370: pcibios_lookup_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int pcibios_lookup_irq(struct pci_dev *dev, int assign);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (0)
Location: arch/x86/pci/irq.c:881
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pirq_enable_irq
  - arch/x86/pci/irq.c:pcibios_fixup_irqs
```
**Symbols:**

```
ffffffff81919aa0-ffffffff8191a02b: pcibios_lookup_irq (STB_LOCAL)
ffffffff8191a336-ffffffff8191a470: pcibios_lookup_irq.cold (STB_LOCAL)
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
