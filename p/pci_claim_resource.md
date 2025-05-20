# Function: <code>pci_claim_resource</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pci_claim_resource(struct pci_dev *dev, int resource);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff8143d1f0)
Location: drivers/pci/setup-res.c:113
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_claim_bridge_resource
  - drivers/pci/setup-bus.c:pci_claim_bridge_resource
  - drivers/pci/quirks.c:quirk_io_region
  - arch/x86/pci/i386.c:pcibios_allocate_rom_resources
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
**Symbols:**

```
ffffffff8143d1f0-ffffffff8143d2d9: pci_claim_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pci_claim_resource(struct pci_dev *dev, int resource);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff81489060)
Location: drivers/pci/setup-res.c:113
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_allocate_dev_resources
  - drivers/pci/quirks.c:quirk_io_region
  - arch/x86/pci/i386.c:pcibios_allocate_rom_resources
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
**Symbols:**

```
ffffffff81489060-ffffffff8148913f: pci_claim_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_claim_resource(struct pci_dev *dev, int resource);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff814aa830)
Location: drivers/pci/setup-res.c:133
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_allocate_dev_resources
  - drivers/pci/quirks.c:quirk_io_region
  - arch/x86/pci/i386.c:pcibios_allocate_rom_resources
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
**Symbols:**

```
ffffffff814aa830-ffffffff814aa915: pci_claim_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_claim_resource(struct pci_dev *dev, int resource);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff814b4b80)
Location: drivers/pci/setup-res.c:133
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_allocate_dev_resources
  - drivers/pci/quirks.c:quirk_io_region
  - arch/x86/pci/i386.c:pcibios_allocate_rom_resources
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
**Symbols:**

```
ffffffff814b4b80-ffffffff814b4c68: pci_claim_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_claim_resource(struct pci_dev *dev, int resource);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff814f43c0)
Location: drivers/pci/setup-res.c:134
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_allocate_dev_resources
  - drivers/pci/quirks.c:quirk_io_region
  - arch/x86/pci/i386.c:pcibios_allocate_rom_resources
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
**Symbols:**

```
ffffffff814f43c0-ffffffff814f44a7: pci_claim_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_claim_resource(struct pci_dev *dev, int resource);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff81524470)
Location: drivers/pci/setup-res.c:130
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_allocate_dev_resources
  - drivers/pci/quirks.c:quirk_io_region
  - arch/x86/pci/i386.c:pcibios_allocate_rom_resources
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
**Symbols:**

```
ffffffff81524470-ffffffff81524557: pci_claim_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_claim_resource(struct pci_dev *dev, int resource);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff8153a2f0)
Location: drivers/pci/setup-res.c:130
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_allocate_dev_resources
  - drivers/pci/quirks.c:quirk_io_region
  - arch/x86/pci/i386.c:pcibios_allocate_rom_resources
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
**Symbols:**

```
ffffffff8153a2f0-ffffffff8153a3d5: pci_claim_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pci_claim_resource(struct pci_dev *dev, int resource);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:130
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_allocate_dev_resources
  - drivers/pci/quirks.c:quirk_io_region
  - arch/x86/pci/i386.c:pcibios_allocate_rom_resources
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
**Symbols:**

```
ffffffff8156a4f2-ffffffff8156a57a: pci_claim_resource.cold (STB_LOCAL)
ffffffff81569d70-ffffffff81569de1: pci_claim_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int pci_claim_resource(struct pci_dev *dev, int resource);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:130
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_allocate_dev_resources
  - drivers/pci/quirks.c:quirk_io_region
  - arch/x86/pci/i386.c:pcibios_allocate_rom_resources
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
**Symbols:**

```
ffffffff8158b4c2-ffffffff8158b54a: pci_claim_resource.cold (STB_LOCAL)
ffffffff8158ad40-ffffffff8158adb4: pci_claim_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int pci_claim_resource(struct pci_dev *dev, int resource);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:130
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_allocate_dev_resources
  - drivers/pci/quirks.c:quirk_io_region
  - arch/x86/pci/i386.c:pcibios_allocate_rom_resources
  - arch/x86/pci/i386.c:pcibios_allocate_dev_resources
```
**Symbols:**

```
ffffffff81632539-ffffffff816325c1: pci_claim_resource.cold (STB_LOCAL)
ffffffff81631ea0-ffffffff81631f11: pci_claim_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int pci_claim_resource(struct pci_dev *dev, int resource);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:131
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_allocate_dev_resources
  - drivers/pci/quirks.c:quirk_io_region
  - arch/x86/pci/i386.c:pcibios_allocate_rom_resources
  - arch/x86/pci/i386.c:pcibios_allocate_dev_resources
```
**Symbols:**

```
ffffffff81bf8215-ffffffff81bf829d: pci_claim_resource.cold (STB_LOCAL)
ffffffff816574a0-ffffffff81657511: pci_claim_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int pci_claim_resource(struct pci_dev *dev, int resource);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:131
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_allocate_dev_resources
  - drivers/pci/quirks.c:quirk_io_region
  - arch/x86/pci/i386.c:pcibios_allocate_rom_resources
  - arch/x86/pci/i386.c:pcibios_allocate_dev_resources
```
**Symbols:**

```
ffffffff81bea0b4-ffffffff81bea13c: pci_claim_resource.cold (STB_LOCAL)
ffffffff81639e10-ffffffff81639e81: pci_claim_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pci_claim_resource(struct pci_dev *dev, int resource);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:131
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_allocate_dev_resources
  - drivers/pci/quirks.c:quirk_io_region
  - arch/x86/pci/i386.c:pcibios_allocate_rom_resources
  - arch/x86/pci/i386.c:pcibios_allocate_dev_resources
```
**Symbols:**

```
ffffffff81ce4eb3-ffffffff81ce4f39: pci_claim_resource.cold (STB_LOCAL)
ffffffff816aa5e0-ffffffff816aa66d: pci_claim_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pci_claim_resource(struct pci_dev *dev, int resource);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:135
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_allocate_dev_resources
  - drivers/pci/setup-bus.c:pci_claim_bridge_resource
  - drivers/pci/setup-bus.c:pci_claim_bridge_resource
  - drivers/pci/quirks.c:quirk_io_region
  - arch/x86/pci/i386.c:pcibios_allocate_rom_resources
  - arch/x86/pci/i386.c:pcibios_allocate_dev_resources
```
**Symbols:**

```
ffffffff81eab93e-ffffffff81eab9bc: pci_claim_resource.cold (STB_LOCAL)
ffffffff817cd4c0-ffffffff817cd55e: pci_claim_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_claim_resource(struct pci_dev *dev, int resource);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff818ec9b0)
Location: drivers/pci/setup-res.c:135
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_allocate_dev_resources
  - drivers/pci/setup-bus.c:pci_claim_bridge_resource
  - drivers/pci/setup-bus.c:pci_claim_bridge_resource
  - drivers/pci/quirks.c:quirk_io_region
  - arch/x86/pci/i386.c:pcibios_allocate_rom_resources
  - arch/x86/pci/i386.c:pcibios_allocate_dev_resources
```
**Symbols:**

```
ffffffff818ec9b0-ffffffff818ecac3: pci_claim_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_claim_resource(struct pci_dev *dev, int resource);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff8192fe90)
Location: drivers/pci/setup-res.c:135
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_allocate_dev_resources
  - drivers/pci/setup-bus.c:pci_claim_bridge_resource
  - drivers/pci/setup-bus.c:pci_claim_bridge_resource
  - drivers/pci/quirks.c:quirk_io_region
  - arch/x86/pci/i386.c:pcibios_allocate_rom_resources
  - arch/x86/pci/i386.c:pcibios_allocate_dev_resources
```
**Symbols:**

```
ffffffff8192fe90-ffffffff8192ffa3: pci_claim_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_claim_resource(struct pci_dev *dev, int resource);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff81978810)
Location: drivers/pci/setup-res.c:136
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_allocate_dev_resources
  - drivers/pci/setup-bus.c:pci_claim_bridge_resource
  - drivers/pci/setup-bus.c:pci_claim_bridge_resource
  - drivers/pci/quirks.c:quirk_io_region
  - arch/x86/pci/i386.c:pcibios_allocate_rom_resources
  - arch/x86/pci/i386.c:pcibios_allocate_dev_resources
```
**Symbols:**

```
ffffffff81978810-ffffffff81978931: pci_claim_resource (STB_GLOBAL)
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
int pci_claim_resource(struct pci_dev *dev, int resource);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffff8000106efa00)
Location: drivers/pci/setup-res.c:130
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_allocate_dev_resources
  - drivers/pci/quirks.c:quirk_io_region
```
**Symbols:**

```
ffff8000106efa00-ffff8000106efaf0: pci_claim_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_claim_resource(struct pci_dev *dev, int resource);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (c088a598)
Location: drivers/pci/setup-res.c:130
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_allocate_dev_resources
  - drivers/pci/quirks.c:quirk_io_region
```
**Symbols:**

```
c088a598-c088a68c: pci_claim_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_claim_resource(struct pci_dev *dev, int resource);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (c00000000086cc50)
Location: drivers/pci/setup-res.c:130
Inline: False
Direct callers:
  - arch/powerpc/kernel/pci-common.c:pcibios_claim_one_bus
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_allocate_dev_resources
  - drivers/pci/quirks.c:quirk_io_region
```
**Symbols:**

```
c00000000086cc50-c00000000086cda4: pci_claim_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_claim_resource(struct pci_dev *dev, int resource);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffe0004c37fe)
Location: drivers/pci/setup-res.c:130
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_allocate_dev_resources
  - drivers/pci/quirks.c:quirk_io_region
```
**Symbols:**

```
ffffffe0004c37fe-ffffffe0004c38e0: pci_claim_resource (STB_GLOBAL)
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
int pci_claim_resource(struct pci_dev *dev, int resource);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:130
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_allocate_dev_resources
  - drivers/pci/quirks.c:quirk_io_region
  - arch/x86/pci/i386.c:pcibios_allocate_rom_resources
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
**Symbols:**

```
ffffffff8157f342-ffffffff8157f3ca: pci_claim_resource.cold (STB_LOCAL)
ffffffff8157ebc0-ffffffff8157ec31: pci_claim_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int pci_claim_resource(struct pci_dev *dev, int resource);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:130
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_allocate_dev_resources
  - drivers/pci/quirks.c:quirk_io_region
  - arch/x86/pci/i386.c:pcibios_allocate_rom_resources
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
**Symbols:**

```
ffffffff8156e122-ffffffff8156e1aa: pci_claim_resource.cold (STB_LOCAL)
ffffffff8156d9a0-ffffffff8156da14: pci_claim_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int pci_claim_resource(struct pci_dev *dev, int resource);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:130
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_allocate_dev_resources
  - drivers/pci/quirks.c:quirk_io_region
  - arch/x86/pci/i386.c:pcibios_allocate_rom_resources
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
**Symbols:**

```
ffffffff8157f212-ffffffff8157f29a: pci_claim_resource.cold (STB_LOCAL)
ffffffff8157ea90-ffffffff8157eb04: pci_claim_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int pci_claim_resource(struct pci_dev *dev, int resource);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:130
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_allocate_dev_resources
  - drivers/pci/quirks.c:quirk_io_region
  - arch/x86/pci/i386.c:pcibios_allocate_rom_resources
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
**Symbols:**

```
ffffffff815996c2-ffffffff8159974a: pci_claim_resource.cold (STB_LOCAL)
ffffffff81598f40-ffffffff81598fb4: pci_claim_resource (STB_GLOBAL)
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
