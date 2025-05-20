# Function: <code>pirq_enable_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pirq_enable_irq(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff816f9fd0)
Location: arch/x86/pci/irq.c:1189
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff816f9fd0-ffffffff816fa1ec: pirq_enable_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pirq_enable_irq(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff8175ed10)
Location: arch/x86/pci/irq.c:1189
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff8175ed10-ffffffff8175ef2c: pirq_enable_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pirq_enable_irq(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff8178b240)
Location: arch/x86/pci/irq.c:1189
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff8178b240-ffffffff8178b45c: pirq_enable_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pirq_enable_irq(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff817aa190)
Location: arch/x86/pci/irq.c:1189
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff817aa190-ffffffff817aa3a5: pirq_enable_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pirq_enable_irq(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff81821660)
Location: arch/x86/pci/irq.c:1190
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff81821660-ffffffff81821875: pirq_enable_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pirq_enable_irq(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff8186b8c0)
Location: arch/x86/pci/irq.c:1191
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff8186b8c0-ffffffff8186bacc: pirq_enable_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pirq_enable_irq(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff8188b9a0)
Location: arch/x86/pci/irq.c:1191
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff8188b9a0-ffffffff8188bbac: pirq_enable_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pirq_enable_irq(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (0)
Location: arch/x86/pci/irq.c:1197
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff818d6190-ffffffff818d630b: pirq_enable_irq (STB_LOCAL)
ffffffff818d65d0-ffffffff818d6657: pirq_enable_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int pirq_enable_irq(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (0)
Location: arch/x86/pci/irq.c:1197
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff81908510-ffffffff8190868b: pirq_enable_irq (STB_LOCAL)
ffffffff81908950-ffffffff819089d7: pirq_enable_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int pirq_enable_irq(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (0)
Location: arch/x86/pci/irq.c:1197
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff81bb8e10-ffffffff81bb8f8b: pirq_enable_irq (STB_LOCAL)
ffffffff81bb92b7-ffffffff81bb933e: pirq_enable_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int pirq_enable_irq(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (0)
Location: arch/x86/pci/irq.c:1197
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff81bcda20-ffffffff81bcdb9b: pirq_enable_irq (STB_LOCAL)
ffffffff81c349d6-ffffffff81c34a5d: pirq_enable_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int pirq_enable_irq(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (0)
Location: arch/x86/pci/irq.c:1197
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff81bc13f0-ffffffff81bc156b: pirq_enable_irq (STB_LOCAL)
ffffffff81c26dbe-ffffffff81c26e45: pirq_enable_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pirq_enable_irq(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (0)
Location: arch/x86/pci/irq.c:1470
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff81c91970-ffffffff81c91aeb: pirq_enable_irq (STB_LOCAL)
ffffffff81d44d49-ffffffff81d44dd0: pirq_enable_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pirq_enable_irq(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (0)
Location: arch/x86/pci/irq.c:1719
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff81e40df0-ffffffff81e40f7e: pirq_enable_irq (STB_LOCAL)
ffffffff81f11c98-ffffffff81f11d1f: pirq_enable_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pirq_enable_irq(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff8201b2b0)
Location: arch/x86/pci/irq.c:1719
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff8201b2b0-ffffffff8201b4b8: pirq_enable_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pirq_enable_irq(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/irq.c (ffffffff8209b930)
Location: arch/x86/pci/irq.c:1719
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff8209b930-ffffffff8209bb38: pirq_enable_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int pirq_enable_irq(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (0)
Location: arch/x86/pci/irq.c:1719
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff82173080-ffffffff821732e1: pirq_enable_irq (STB_LOCAL)
ffffffff8221a652-ffffffff8221a67c: pirq_enable_irq.cold (STB_LOCAL)
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
int pirq_enable_irq(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (0)
Location: arch/x86/pci/irq.c:1197
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff818a78d0-ffffffff818a7a4b: pirq_enable_irq (STB_LOCAL)
ffffffff818a7d10-ffffffff818a7d97: pirq_enable_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int pirq_enable_irq(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (0)
Location: arch/x86/pci/irq.c:1197
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff818623f0-ffffffff8186256b: pirq_enable_irq (STB_LOCAL)
ffffffff81862830-ffffffff818628b7: pirq_enable_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int pirq_enable_irq(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (0)
Location: arch/x86/pci/irq.c:1197
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff818f8f30-ffffffff818f90ab: pirq_enable_irq (STB_LOCAL)
ffffffff818f9370-ffffffff818f93f7: pirq_enable_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int pirq_enable_irq(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/irq.c (0)
Location: arch/x86/pci/irq.c:1197
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
```
**Symbols:**

```
ffffffff8191a030-ffffffff8191a1ab: pirq_enable_irq (STB_LOCAL)
ffffffff8191a470-ffffffff8191a4f7: pirq_enable_irq.cold (STB_LOCAL)
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
