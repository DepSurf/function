# Function: <code>pcibios_setup_bridge</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pcibios_setup_bridge(struct pci_bus *bus, long unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8148afc0)
Location: drivers/pci/setup-bus.c:698
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff8148afc0-ffffffff8148afcb: pcibios_setup_bridge (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pcibios_setup_bridge(struct pci_bus *bus, long unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff814ac7b0)
Location: drivers/pci/setup-bus.c:699
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff814ac7b0-ffffffff814ac7bb: pcibios_setup_bridge (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pcibios_setup_bridge(struct pci_bus *bus, long unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff814b6b30)
Location: drivers/pci/setup-bus.c:690
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff814b6b30-ffffffff814b6b3b: pcibios_setup_bridge (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pcibios_setup_bridge(struct pci_bus *bus, long unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff814f6c80)
Location: drivers/pci/setup-bus.c:690
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff814f6c80-ffffffff814f6c8b: pcibios_setup_bridge (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pcibios_setup_bridge(struct pci_bus *bus, long unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff81527800)
Location: drivers/pci/setup-bus.c:685
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff81527800-ffffffff8152780b: pcibios_setup_bridge (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pcibios_setup_bridge(struct pci_bus *bus, long unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8153d690)
Location: drivers/pci/setup-bus.c:685
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff8153d690-ffffffff8153d69b: pcibios_setup_bridge (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pcibios_setup_bridge(struct pci_bus *bus, long unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8156cd30)
Location: drivers/pci/setup-bus.c:682
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff8156cd30-ffffffff8156cd3b: pcibios_setup_bridge (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pcibios_setup_bridge(struct pci_bus *bus, long unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8158dd10)
Location: drivers/pci/setup-bus.c:682
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff8158dd10-ffffffff8158dd1b: pcibios_setup_bridge (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pcibios_setup_bridge(struct pci_bus *bus, long unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff81635940)
Location: drivers/pci/setup-bus.c:683
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff81635940-ffffffff8163594b: pcibios_setup_bridge (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pcibios_setup_bridge(struct pci_bus *bus, long unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8165aa00)
Location: drivers/pci/setup-bus.c:684
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff8165aa00-ffffffff8165aa0b: pcibios_setup_bridge (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pcibios_setup_bridge(struct pci_bus *bus, long unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8163cf40)
Location: drivers/pci/setup-bus.c:684
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff8163cf40-ffffffff8163cf4b: pcibios_setup_bridge (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pcibios_setup_bridge(struct pci_bus *bus, long unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff816ad9a0)
Location: drivers/pci/setup-bus.c:684
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff816ad9a0-ffffffff816ad9ab: pcibios_setup_bridge (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pcibios_setup_bridge(struct pci_bus *bus, long unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff817d0e20)
Location: drivers/pci/setup-bus.c:684
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff817d0e20-ffffffff817d0e2f: pcibios_setup_bridge (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pcibios_setup_bridge(struct pci_bus *bus, long unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff818f11d0)
Location: drivers/pci/setup-bus.c:684
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_setup_bridge
```
**Symbols:**

```
ffffffff818f11d0-ffffffff818f11df: pcibios_setup_bridge (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pcibios_setup_bridge(struct pci_bus *bus, long unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff819345f0)
Location: drivers/pci/setup-bus.c:681
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_setup_bridge
```
**Symbols:**

```
ffffffff819345f0-ffffffff819345ff: pcibios_setup_bridge (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pcibios_setup_bridge(struct pci_bus *bus, long unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8197d310)
Location: drivers/pci/setup-bus.c:690
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_setup_bridge
```
**Symbols:**

```
ffffffff8197d310-ffffffff8197d31f: pcibios_setup_bridge (STB_WEAK)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void pcibios_setup_bridge(struct pci_bus *bus, long unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffff8000106f2ff0)
Location: drivers/pci/setup-bus.c:682
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffff8000106f2ff0-ffff8000106f3008: pcibios_setup_bridge (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pcibios_setup_bridge(struct pci_bus *bus, long unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (c088da84)
Location: drivers/pci/setup-bus.c:682
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
c088da84-c088da9c: pcibios_setup_bridge (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pcibios_setup_bridge(struct pci_bus *bus, long unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/pci-common.c (c00000000006d330)
Location: arch/powerpc/kernel/pci-common.c:209
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
c00000000006d330-c00000000006d37c: pcibios_setup_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pcibios_setup_bridge(struct pci_bus *bus, long unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffe0004c63d4)
Location: drivers/pci/setup-bus.c:682
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffe0004c63d4-ffffffe0004c63ee: pcibios_setup_bridge (STB_WEAK)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void pcibios_setup_bridge(struct pci_bus *bus, long unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff81581b90)
Location: drivers/pci/setup-bus.c:682
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff81581b90-ffffffff81581b9b: pcibios_setup_bridge (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pcibios_setup_bridge(struct pci_bus *bus, long unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff81570970)
Location: drivers/pci/setup-bus.c:682
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff81570970-ffffffff8157097b: pcibios_setup_bridge (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pcibios_setup_bridge(struct pci_bus *bus, long unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff81581a60)
Location: drivers/pci/setup-bus.c:682
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff81581a60-ffffffff81581a6b: pcibios_setup_bridge (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pcibios_setup_bridge(struct pci_bus *bus, long unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8159bf10)
Location: drivers/pci/setup-bus.c:682
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bridge_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff8159bf10-ffffffff8159bf1b: pcibios_setup_bridge (STB_WEAK)
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
