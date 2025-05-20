# Function: <code>pci_claim_bridge_resource</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pci_claim_bridge_resource(struct pci_dev *bridge, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8143f1d0)
Location: drivers/pci/setup-bus.c:708
Inline: False
Direct callers:
  - arch/x86/pci/i386.c:pcibios_allocate_bus_resources
```
**Symbols:**

```
ffffffff8143f1d0-ffffffff8143f261: pci_claim_bridge_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int pci_claim_bridge_resource(struct pci_dev *bridge, int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8148b000)
Location: drivers/pci/setup-bus.c:712
Inline: True
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_allocate_resources
  - arch/x86/pci/i386.c:pcibios_allocate_bus_resources
```
**Symbols:**

```
ffffffff8148b000-ffffffff8148b091: pci_claim_bridge_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int pci_claim_bridge_resource(struct pci_dev *bridge, int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff814ac7f0)
Location: drivers/pci/setup-bus.c:713
Inline: True
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_allocate_resources
  - arch/x86/pci/i386.c:pcibios_allocate_bus_resources
```
**Symbols:**

```
ffffffff814ac7f0-ffffffff814ac881: pci_claim_bridge_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int pci_claim_bridge_resource(struct pci_dev *bridge, int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff814b6b70)
Location: drivers/pci/setup-bus.c:704
Inline: True
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_allocate_resources
  - arch/x86/pci/i386.c:pcibios_allocate_bus_resources
```
**Symbols:**

```
ffffffff814b6b70-ffffffff814b6c01: pci_claim_bridge_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int pci_claim_bridge_resource(struct pci_dev *bridge, int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff814f6cc0)
Location: drivers/pci/setup-bus.c:704
Inline: True
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_allocate_resources
  - arch/x86/pci/i386.c:pcibios_allocate_bus_resources
```
**Symbols:**

```
ffffffff814f6cc0-ffffffff814f6d51: pci_claim_bridge_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int pci_claim_bridge_resource(struct pci_dev *bridge, int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff81527840)
Location: drivers/pci/setup-bus.c:699
Inline: True
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_allocate_resources
  - arch/x86/pci/i386.c:pcibios_allocate_bus_resources
```
**Symbols:**

```
ffffffff81527840-ffffffff815278d4: pci_claim_bridge_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int pci_claim_bridge_resource(struct pci_dev *bridge, int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8153d6d0)
Location: drivers/pci/setup-bus.c:699
Inline: True
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_allocate_resources
  - arch/x86/pci/i386.c:pcibios_allocate_bus_resources
```
**Symbols:**

```
ffffffff8153d6d0-ffffffff8153d764: pci_claim_bridge_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int pci_claim_bridge_resource(struct pci_dev *bridge, int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8156cd70)
Location: drivers/pci/setup-bus.c:696
Inline: True
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_allocate_resources
  - arch/x86/pci/i386.c:pcibios_allocate_bus_resources
```
**Symbols:**

```
ffffffff8156cd70-ffffffff8156ce00: pci_claim_bridge_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int pci_claim_bridge_resource(struct pci_dev *bridge, int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8158dd50)
Location: drivers/pci/setup-bus.c:696
Inline: True
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_allocate_resources
  - arch/x86/pci/i386.c:pcibios_allocate_bus_resources
```
**Symbols:**

```
ffffffff8158dd50-ffffffff8158dde0: pci_claim_bridge_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int pci_claim_bridge_resource(struct pci_dev *bridge, int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff81635980)
Location: drivers/pci/setup-bus.c:697
Inline: True
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_allocate_resources
  - arch/x86/pci/i386.c:pcibios_allocate_bus_resources
```
**Symbols:**

```
ffffffff81635980-ffffffff81635a15: pci_claim_bridge_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int pci_claim_bridge_resource(struct pci_dev *bridge, int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8165aa40)
Location: drivers/pci/setup-bus.c:698
Inline: True
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_allocate_resources
  - arch/x86/pci/i386.c:pcibios_allocate_bus_resources
```
**Symbols:**

```
ffffffff8165aa40-ffffffff8165aad5: pci_claim_bridge_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int pci_claim_bridge_resource(struct pci_dev *bridge, int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8163cf80)
Location: drivers/pci/setup-bus.c:698
Inline: True
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_allocate_resources
  - arch/x86/pci/i386.c:pcibios_allocate_bus_resources
```
**Symbols:**

```
ffffffff8163cf80-ffffffff8163d015: pci_claim_bridge_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int pci_claim_bridge_resource(struct pci_dev *bridge, int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff816ad9e0)
Location: drivers/pci/setup-bus.c:698
Inline: True
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_allocate_resources
  - arch/x86/pci/i386.c:pcibios_allocate_bus_resources
```
**Symbols:**

```
ffffffff816ad9e0-ffffffff816ada75: pci_claim_bridge_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_claim_bridge_resource(struct pci_dev *bridge, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff817d0e70)
Location: drivers/pci/setup-bus.c:698
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_allocate_resources
  - arch/x86/pci/i386.c:pcibios_allocate_bus_resources
```
**Symbols:**

```
ffffffff817d0e70-ffffffff817d0f0b: pci_claim_bridge_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_claim_bridge_resource(struct pci_dev *bridge, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff818f1280)
Location: drivers/pci/setup-bus.c:698
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_allocate_resources
  - arch/x86/pci/i386.c:pcibios_allocate_bus_resources
```
**Symbols:**

```
ffffffff818f1280-ffffffff818f131b: pci_claim_bridge_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_claim_bridge_resource(struct pci_dev *bridge, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff819346a0)
Location: drivers/pci/setup-bus.c:695
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_allocate_resources
  - arch/x86/pci/i386.c:pcibios_allocate_bus_resources
```
**Symbols:**

```
ffffffff819346a0-ffffffff81934739: pci_claim_bridge_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_claim_bridge_resource(struct pci_dev *bridge, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8197d3c0)
Location: drivers/pci/setup-bus.c:704
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_allocate_resources
  - arch/x86/pci/i386.c:pcibios_allocate_bus_resources
```
**Symbols:**

```
ffffffff8197d3c0-ffffffff8197d459: pci_claim_bridge_resource (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int pci_claim_bridge_resource(struct pci_dev *bridge, int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffff8000106f3048)
Location: drivers/pci/setup-bus.c:696
Inline: True
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_allocate_resources
```
**Symbols:**

```
ffff8000106f3048-ffff8000106f310c: pci_claim_bridge_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int pci_claim_bridge_resource(struct pci_dev *bridge, int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (c088dacc)
Location: drivers/pci/setup-bus.c:696
Inline: True
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_allocate_resources
```
**Symbols:**

```
c088dacc-c088db84: pci_claim_bridge_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int pci_claim_bridge_resource(struct pci_dev *bridge, int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (c000000000871240)
Location: drivers/pci/setup-bus.c:696
Inline: True
Direct callers:
  - arch/powerpc/kernel/pci-common.c:pcibios_claim_one_bus
  - arch/powerpc/kernel/pci-common.c:pcibios_allocate_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_allocate_resources
```
**Symbols:**

```
c000000000871240-c00000000087137c: pci_claim_bridge_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int pci_claim_bridge_resource(struct pci_dev *bridge, int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffe0004c6430)
Location: drivers/pci/setup-bus.c:696
Inline: True
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_allocate_resources
```
**Symbols:**

```
ffffffe0004c6430-ffffffe0004c64d8: pci_claim_bridge_resource (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int pci_claim_bridge_resource(struct pci_dev *bridge, int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff81581bd0)
Location: drivers/pci/setup-bus.c:696
Inline: True
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_allocate_resources
  - arch/x86/pci/i386.c:pcibios_allocate_bus_resources
```
**Symbols:**

```
ffffffff81581bd0-ffffffff81581c60: pci_claim_bridge_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int pci_claim_bridge_resource(struct pci_dev *bridge, int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff815709b0)
Location: drivers/pci/setup-bus.c:696
Inline: True
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_allocate_resources
  - arch/x86/pci/i386.c:pcibios_allocate_bus_resources
```
**Symbols:**

```
ffffffff815709b0-ffffffff81570a40: pci_claim_bridge_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int pci_claim_bridge_resource(struct pci_dev *bridge, int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff81581aa0)
Location: drivers/pci/setup-bus.c:696
Inline: True
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_allocate_resources
  - arch/x86/pci/i386.c:pcibios_allocate_bus_resources
```
**Symbols:**

```
ffffffff81581aa0-ffffffff81581b30: pci_claim_bridge_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int pci_claim_bridge_resource(struct pci_dev *bridge, int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8159bf50)
Location: drivers/pci/setup-bus.c:696
Inline: True
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_allocate_resources
  - arch/x86/pci/i386.c:pcibios_allocate_bus_resources
```
**Symbols:**

```
ffffffff8159bf50-ffffffff8159bfe0: pci_claim_bridge_resource (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
