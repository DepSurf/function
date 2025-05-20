# Function: <code>pci_bus_generic_read_dev_vendor_id</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool pci_bus_generic_read_dev_vendor_id(struct pci_bus *bus, int devfn, u32 *l, int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (ffffffff8152c060)
Location: drivers/pci/probe.c:2258
Inline: True
Direct callers:
  - drivers/pci/quirks.c:pci_idt_bus_quirk
```
**Symbols:**

```
ffffffff8152df8c-ffffffff8152e026: pci_bus_generic_read_dev_vendor_id.cold.45 (STB_LOCAL)
ffffffff8152c030-ffffffff8152c124: pci_bus_generic_read_dev_vendor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool pci_bus_generic_read_dev_vendor_id(struct pci_bus *bus, int devfn, u32 *l, int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (ffffffff8155aa00)
Location: drivers/pci/probe.c:2484
Inline: True
Direct callers:
  - drivers/pci/quirks.c:pci_idt_bus_quirk
```
**Symbols:**

```
ffffffff8155d364-ffffffff8155d3ff: pci_bus_generic_read_dev_vendor_id.cold (STB_LOCAL)
ffffffff8155a9d0-ffffffff8155aac8: pci_bus_generic_read_dev_vendor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool pci_bus_generic_read_dev_vendor_id(struct pci_bus *bus, int devfn, u32 *l, int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (ffffffff8157ba90)
Location: drivers/pci/probe.c:2222
Inline: True
Direct callers:
  - drivers/pci/quirks.c:pci_idt_bus_quirk
```
**Symbols:**

```
ffffffff8157e41e-ffffffff8157e4b9: pci_bus_generic_read_dev_vendor_id.cold (STB_LOCAL)
ffffffff8157ba60-ffffffff8157bb58: pci_bus_generic_read_dev_vendor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool pci_bus_generic_read_dev_vendor_id(struct pci_bus *bus, int devfn, u32 *l, int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (ffffffff81621210)
Location: drivers/pci/probe.c:2290
Inline: True
Direct callers:
  - drivers/pci/quirks.c:pci_idt_bus_quirk
```
**Symbols:**

```
ffffffff81623907-ffffffff816239a2: pci_bus_generic_read_dev_vendor_id.cold (STB_LOCAL)
ffffffff816211e0-ffffffff816212d8: pci_bus_generic_read_dev_vendor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool pci_bus_generic_read_dev_vendor_id(struct pci_bus *bus, int devfn, u32 *l, int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (ffffffff81647d80)
Location: drivers/pci/probe.c:2297
Inline: True
Direct callers:
  - drivers/pci/quirks.c:pci_idt_bus_quirk
```
**Symbols:**

```
ffffffff81bf7611-ffffffff81bf76ac: pci_bus_generic_read_dev_vendor_id.cold (STB_LOCAL)
ffffffff81647d50-ffffffff81647e48: pci_bus_generic_read_dev_vendor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool pci_bus_generic_read_dev_vendor_id(struct pci_bus *bus, int devfn, u32 *l, int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (ffffffff8162a9c0)
Location: drivers/pci/probe.c:2340
Inline: True
Direct callers:
  - drivers/pci/quirks.c:pci_idt_bus_quirk
```
**Symbols:**

```
ffffffff81be9437-ffffffff81be94d2: pci_bus_generic_read_dev_vendor_id.cold (STB_LOCAL)
ffffffff8162a990-ffffffff8162aa88: pci_bus_generic_read_dev_vendor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool pci_bus_generic_read_dev_vendor_id(struct pci_bus *bus, int devfn, u32 *l, int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (ffffffff81699ea0)
Location: drivers/pci/probe.c:2387
Inline: True
Direct callers:
  - drivers/pci/quirks.c:pci_idt_bus_quirk
```
**Symbols:**

```
ffffffff81ce3ddd-ffffffff81ce3e78: pci_bus_generic_read_dev_vendor_id.cold (STB_LOCAL)
ffffffff81699e70-ffffffff81699f68: pci_bus_generic_read_dev_vendor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool pci_bus_generic_read_dev_vendor_id(struct pci_bus *bus, int devfn, u32 *l, int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (ffffffff817bb4ac)
Location: drivers/pci/probe.c:2362
Inline: True
Direct callers:
  - drivers/pci/quirks.c:pci_idt_bus_quirk
```
**Symbols:**

```
ffffffff81eaa82e-ffffffff81eaa8d0: pci_bus_generic_read_dev_vendor_id.cold (STB_LOCAL)
ffffffff817bb480-ffffffff817bb570: pci_bus_generic_read_dev_vendor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool pci_bus_generic_read_dev_vendor_id(struct pci_bus *bus, int devfn, u32 *l, int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff818d6ea0)
Location: drivers/pci/probe.c:2374
Inline: True
Direct callers:
  - drivers/pci/quirks.c:pci_idt_bus_quirk
```
**Symbols:**

```
ffffffff818d6ea0-ffffffff818d7036: pci_bus_generic_read_dev_vendor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool pci_bus_generic_read_dev_vendor_id(struct pci_bus *bus, int devfn, u32 *l, int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8191a120)
Location: drivers/pci/probe.c:2385
Inline: True
Direct callers:
  - drivers/pci/quirks.c:pci_idt_bus_quirk
```
**Symbols:**

```
ffffffff8191a120-ffffffff8191a2b6: pci_bus_generic_read_dev_vendor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool pci_bus_generic_read_dev_vendor_id(struct pci_bus *bus, int devfn, u32 *l, int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81962520)
Location: drivers/pci/probe.c:2434
Inline: True
Direct callers:
  - drivers/pci/quirks.c:pci_idt_bus_quirk
```
**Symbols:**

```
ffffffff81962520-ffffffff819626b6: pci_bus_generic_read_dev_vendor_id (STB_GLOBAL)
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
bool pci_bus_generic_read_dev_vendor_id(struct pci_bus *bus, int devfn, u32 *l, int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffff8000106def00)
Location: drivers/pci/probe.c:2222
Inline: True
Direct callers:
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:pci_idt_bus_quirk
```
**Symbols:**

```
ffff8000106def00-ffff8000106df0b4: pci_bus_generic_read_dev_vendor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool pci_bus_generic_read_dev_vendor_id(struct pci_bus *bus, int devfn, u32 *l, int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c087abf0)
Location: drivers/pci/probe.c:2222
Inline: True
Direct callers:
  - drivers/pci/quirks.c:pci_idt_bus_quirk
```
**Symbols:**

```
c087abf0-c087ad78: pci_bus_generic_read_dev_vendor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool pci_bus_generic_read_dev_vendor_id(struct pci_bus *bus, int devfn, u32 *l, int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c000000000857410)
Location: drivers/pci/probe.c:2222
Inline: True
Direct callers:
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:pci_idt_bus_quirk
```
**Symbols:**

```
c000000000857410-c00000000085767c: pci_bus_generic_read_dev_vendor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool pci_bus_generic_read_dev_vendor_id(struct pci_bus *bus, int devfn, u32 *l, int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffe0004b701a)
Location: drivers/pci/probe.c:2222
Inline: True
Direct callers:
  - drivers/pci/quirks.c:pci_idt_bus_quirk
  - drivers/pci/quirks.c:pci_idt_bus_quirk
```
**Symbols:**

```
ffffffe0004b701a-ffffffe0004b7164: pci_bus_generic_read_dev_vendor_id (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool pci_bus_generic_read_dev_vendor_id(struct pci_bus *bus, int devfn, u32 *l, int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (ffffffff8156ffb0)
Location: drivers/pci/probe.c:2222
Inline: True
Direct callers:
  - drivers/pci/quirks.c:pci_idt_bus_quirk
```
**Symbols:**

```
ffffffff8157293e-ffffffff815729d9: pci_bus_generic_read_dev_vendor_id.cold (STB_LOCAL)
ffffffff8156ff80-ffffffff81570078: pci_bus_generic_read_dev_vendor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool pci_bus_generic_read_dev_vendor_id(struct pci_bus *bus, int devfn, u32 *l, int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (ffffffff8155e710)
Location: drivers/pci/probe.c:2222
Inline: True
Direct callers:
  - drivers/pci/quirks.c:pci_idt_bus_quirk
```
**Symbols:**

```
ffffffff8156109e-ffffffff81561139: pci_bus_generic_read_dev_vendor_id.cold (STB_LOCAL)
ffffffff8155e6e0-ffffffff8155e7d8: pci_bus_generic_read_dev_vendor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool pci_bus_generic_read_dev_vendor_id(struct pci_bus *bus, int devfn, u32 *l, int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (ffffffff8156f7e0)
Location: drivers/pci/probe.c:2222
Inline: True
Direct callers:
  - drivers/pci/quirks.c:pci_idt_bus_quirk
```
**Symbols:**

```
ffffffff8157216e-ffffffff81572209: pci_bus_generic_read_dev_vendor_id.cold (STB_LOCAL)
ffffffff8156f7b0-ffffffff8156f8a8: pci_bus_generic_read_dev_vendor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool pci_bus_generic_read_dev_vendor_id(struct pci_bus *bus, int devfn, u32 *l, int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (ffffffff81589cc0)
Location: drivers/pci/probe.c:2222
Inline: True
Direct callers:
  - drivers/pci/quirks.c:pci_idt_bus_quirk
```
**Symbols:**

```
ffffffff8158c64e-ffffffff8158c6e9: pci_bus_generic_read_dev_vendor_id.cold (STB_LOCAL)
ffffffff81589c90-ffffffff81589d88: pci_bus_generic_read_dev_vendor_id (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
