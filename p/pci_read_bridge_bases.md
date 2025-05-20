# Function: <code>pci_read_bridge_bases</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pci_read_bridge_bases(struct pci_bus *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814309f0)
Location: drivers/pci/probe.c:453
Inline: False
Direct callers:
  - arch/x86/pci/common.c:pcibios_fixup_bus
```
**Symbols:**

```
ffffffff814309f0-ffffffff81430e18: pci_read_bridge_bases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pci_read_bridge_bases(struct pci_bus *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8147c170)
Location: drivers/pci/probe.c:456
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_allocate_resources
  - arch/x86/pci/common.c:pcibios_fixup_bus
```
**Symbols:**

```
ffffffff8147c170-ffffffff8147c5a7: pci_read_bridge_bases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pci_read_bridge_bases(struct pci_bus *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8149d6d0)
Location: drivers/pci/probe.c:457
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_allocate_resources
  - arch/x86/pci/common.c:pcibios_fixup_bus
```
**Symbols:**

```
ffffffff8149d6d0-ffffffff8149db07: pci_read_bridge_bases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pci_read_bridge_bases(struct pci_bus *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814a75b0)
Location: drivers/pci/probe.c:457
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_allocate_resources
  - arch/x86/pci/common.c:pcibios_fixup_bus
```
**Symbols:**

```
ffffffff814a75b0-ffffffff814a79c0: pci_read_bridge_bases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pci_read_bridge_bases(struct pci_bus *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814e5f00)
Location: drivers/pci/probe.c:457
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_allocate_resources
  - arch/x86/pci/common.c:pcibios_fixup_bus
```
**Symbols:**

```
ffffffff814e5f00-ffffffff814e6310: pci_read_bridge_bases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pci_read_bridge_bases(struct pci_bus *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81515380)
Location: drivers/pci/probe.c:467
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_allocate_resources
  - arch/x86/pci/common.c:pcibios_fixup_bus
```
**Symbols:**

```
ffffffff81515380-ffffffff8151578e: pci_read_bridge_bases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pci_read_bridge_bases(struct pci_bus *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8152aaa0)
Location: drivers/pci/probe.c:466
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_allocate_resources
  - arch/x86/pci/common.c:pcibios_fixup_bus
```
**Symbols:**

```
ffffffff8152aaa0-ffffffff8152aeae: pci_read_bridge_bases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void pci_read_bridge_bases(struct pci_bus *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:517
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_allocate_resources
  - arch/x86/pci/common.c:pcibios_fixup_bus
```
**Symbols:**

```
ffffffff8155c84c-ffffffff8155cbde: pci_read_bridge_bases.cold (STB_LOCAL)
ffffffff8155a190-ffffffff8155a1e3: pci_read_bridge_bases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void pci_read_bridge_bases(struct pci_bus *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:512
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_allocate_resources
  - arch/x86/pci/common.c:pcibios_fixup_bus
```
**Symbols:**

```
ffffffff8157d8b4-ffffffff8157dc4b: pci_read_bridge_bases.cold (STB_LOCAL)
ffffffff8157b200-ffffffff8157b253: pci_read_bridge_bases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void pci_read_bridge_bases(struct pci_bus *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:513
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_allocate_resources
  - arch/x86/pci/common.c:pcibios_fixup_bus
```
**Symbols:**

```
ffffffff816231f5-ffffffff81623363: pci_read_bridge_bases.cold (STB_LOCAL)
ffffffff81620da0-ffffffff81620df3: pci_read_bridge_bases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void pci_read_bridge_bases(struct pci_bus *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:513
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_allocate_resources
  - arch/x86/pci/common.c:pcibios_fixup_bus
```
**Symbols:**

```
ffffffff81bf73db-ffffffff81bf7549: pci_read_bridge_bases.cold (STB_LOCAL)
ffffffff81647440-ffffffff81647493: pci_read_bridge_bases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void pci_read_bridge_bases(struct pci_bus *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:514
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_allocate_resources
  - arch/x86/pci/common.c:pcibios_fixup_bus
```
**Symbols:**

```
ffffffff81be8f83-ffffffff81be9315: pci_read_bridge_bases.cold (STB_LOCAL)
ffffffff81629d40-ffffffff81629d93: pci_read_bridge_bases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pci_read_bridge_bases(struct pci_bus *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:515
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_allocate_resources
  - arch/x86/pci/common.c:pcibios_fixup_bus
```
**Symbols:**

```
ffffffff81ce33b3-ffffffff81ce3745: pci_read_bridge_bases.cold (STB_LOCAL)
ffffffff81699740-ffffffff81699793: pci_read_bridge_bases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pci_read_bridge_bases(struct pci_bus *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:514
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_allocate_resources
  - arch/x86/pci/common.c:pcibios_fixup_bus
```
**Symbols:**

```
ffffffff81ea9ec8-ffffffff81eaa2ae: pci_read_bridge_bases.cold (STB_LOCAL)
ffffffff817bacf0-ffffffff817bad54: pci_read_bridge_bases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_read_bridge_bases(struct pci_bus *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff818d5d30)
Location: drivers/pci/probe.c:514
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_allocate_resources
  - arch/x86/pci/common.c:pcibios_fixup_bus
```
**Symbols:**

```
ffffffff818d5d30-ffffffff818d6199: pci_read_bridge_bases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_read_bridge_bases(struct pci_bus *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81918f70)
Location: drivers/pci/probe.c:514
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_allocate_resources
  - arch/x86/pci/common.c:pcibios_fixup_bus
```
**Symbols:**

```
ffffffff81918f70-ffffffff819193d3: pci_read_bridge_bases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_read_bridge_bases(struct pci_bus *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81961620)
Location: drivers/pci/probe.c:525
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_allocate_resources
  - arch/x86/pci/common.c:pcibios_fixup_bus
```
**Symbols:**

```
ffffffff81961620-ffffffff8196175c: pci_read_bridge_bases (STB_GLOBAL)
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
void pci_read_bridge_bases(struct pci_bus *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffff8000106ddcc0)
Location: drivers/pci/probe.c:512
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_allocate_resources
```
**Symbols:**

```
ffff8000106ddcc0-ffff8000106de050: pci_read_bridge_bases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_read_bridge_bases(struct pci_bus *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c08798f0)
Location: drivers/pci/probe.c:512
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_allocate_resources
```
**Symbols:**

```
c08798f0-c0879c9c: pci_read_bridge_bases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pci_read_bridge_bases(struct pci_bus *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c000000000856220)
Location: drivers/pci/probe.c:512
Inline: False
Direct callers:
  - arch/powerpc/kernel/pci-common.c:pcibios_fixup_bus
  - drivers/pci/setup-bus.c:pci_bus_allocate_resources
```
**Symbols:**

```
c000000000856220-c000000000856670: pci_read_bridge_bases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pci_read_bridge_bases(struct pci_bus *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffe0004b5fa6)
Location: drivers/pci/probe.c:512
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_allocate_resources
```
**Symbols:**

```
ffffffe0004b5fa6-ffffffe0004b62dc: pci_read_bridge_bases (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void pci_read_bridge_bases(struct pci_bus *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:512
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_allocate_resources
  - arch/x86/pci/common.c:pcibios_fixup_bus
```
**Symbols:**

```
ffffffff81571dd4-ffffffff8157216b: pci_read_bridge_bases.cold (STB_LOCAL)
ffffffff8156f720-ffffffff8156f773: pci_read_bridge_bases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void pci_read_bridge_bases(struct pci_bus *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:512
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_allocate_resources
  - arch/x86/pci/common.c:pcibios_fixup_bus
```
**Symbols:**

```
ffffffff81560534-ffffffff815608cb: pci_read_bridge_bases.cold (STB_LOCAL)
ffffffff8155de80-ffffffff8155ded3: pci_read_bridge_bases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void pci_read_bridge_bases(struct pci_bus *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:512
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_allocate_resources
  - arch/x86/pci/common.c:pcibios_fixup_bus
```
**Symbols:**

```
ffffffff81571604-ffffffff8157199b: pci_read_bridge_bases.cold (STB_LOCAL)
ffffffff8156ef50-ffffffff8156efa3: pci_read_bridge_bases (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void pci_read_bridge_bases(struct pci_bus *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:512
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_allocate_resources
  - arch/x86/pci/common.c:pcibios_fixup_bus
```
**Symbols:**

```
ffffffff8158bae4-ffffffff8158be7b: pci_read_bridge_bases.cold (STB_LOCAL)
ffffffff81589430-ffffffff81589483: pci_read_bridge_bases (STB_GLOBAL)
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
